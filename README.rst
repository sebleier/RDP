RDP
===

The Ramer–Douglas–Peucker algorithm roughly ported from the pseudo-code provided
by http://en.wikipedia.org/wiki/Ramer%E2%80%93Douglas%E2%80%93Peucker_algorithm

Example Usage::

    >>> from RDP import rdp
    >>> line = [(0,0),(1,0),(2,0),(2,1),(2,2),(1,2),(0,2),(0,1),(0,0)]
    >>> print rdp(line, 1.0)
    [(0, 0), (2, 0), (2, 2), (0, 2), (0, 0)]

