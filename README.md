[![Build Status](https://travis-ci.org/nephia/Nephia-Plugin-CSRFDefender.png?branch=master)](https://travis-ci.org/nephia/Nephia-Plugin-CSRFDefender) [![Coverage Status](https://coveralls.io/repos/nephia/Nephia-Plugin-CSRFDefender/badge.png?branch=master)](https://coveralls.io/r/nephia/Nephia-Plugin-CSRFDefender?branch=master)
# NAME

Nephia::Plugin::CSRFDefender - CSRF Defender Plugin for Nephia

# SYNOPSIS

    package MyApp;
    use strict;
    use warnings;
    use Nephia plugins => [
        'PlackSession',
        'CSRFDefender'
    ];

# DESCRIPTION

Nephia::Plugin::CSRFDefender denies CSRF request.

# METHODS

- get\_csrf\_defender\_token()

    Get a CSRF defender token.

- validate\_csrf()

    Validate CSRF token manually.

# SEE ALSO

[Nephia](http://search.cpan.org/perldoc?Nephia)

[Amon2::Plugin::Web::CSRFDefender](http://search.cpan.org/perldoc?Amon2::Plugin::Web::CSRFDefender)

# LICENSE

Copyright (C) papix.

This library is free software; you can redistribute it and/or modify
it under the same terms as Perl itself.

# AUTHOR

papix <mail@papix.net>
