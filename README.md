<!--

# PyPI

- [Pythons PyPI / PIP](https://pypi.org) Faster API Client.
*(WIP, everything is subject to change on future, join the development!)*


# Features

- [Design by Contract, Contract Programming](https://dev.to/juancarlospaco/design-by-contract-immutability-side-effects-and-gulag-44fk).
- Security Hardened by default (based from [Gentoo Hardened](https://wiki.gentoo.org/wiki/Hardened_Gentoo) and [Debian Hardened](https://wiki.debian.org/Hardening), checked with [`hardening-check`](https://bitbucket.org/Alexander-Shukaev/hardening-check)).
- Coded following the [Power of 10: NASA Coding guidelines for safety-critical code](https://en.wikipedia.org/wiki/The_Power_of_10:_Rules_for_Developing_Safety-Critical_Code#Rules) (as much as possible).
- No Regular Expressions used on the Core, [No Regex Bugs and Vulnerabilities](https://blog.cloudflare.com/details-of-the-cloudflare-outage-on-july-2-2019).
- Compiled machine code performance, as fast as optimized hand crafted C.
- Faster than Cython, Pypy, Go, NodeJS, D.
- High performance with low resources (RPi, VPS, cloud, old pc, etc).
- Works fully independently, even with PIP/Python/Virtualenv completely broken.
- Immutable programming, No Global Mutable State.
- Single file binary, it can even delete itself after use.
- Single file source code, KISS.
- 0 Dependencies.
- ~750Kb file size.
- No Installs, no setups, just copy & paste and run (even on Alpine).
- DRY code via Templates.
- Self-Linting, Self-Documented.
- Real Inferred Static Typed.
- Colored output on the Terminal.
- Project skeleton creator to create your own new Python projects.
- Wont save any passwords, databases, keys, secrets, to disk nor Internet.
- No temporary folders nor files.
- Optimize Python native module binary (PIP Wont optimize binaries,it left all Debugging on)
- Not meant as a drop-in replacement for anything pre-existing.
- 1 language for the whole stack, including high performance modules without requiring C.
- No Global Interpreter Lock.
- No user Tracking Analytics by default.
- No YAML used on the Core, No YAML Vulnerabilities (you can still use YAML).
- No `node_modules/`


# API Bugs

From XML-RPC API Server-side this endpoints wont work anymore:

- `release_downloads`, `top_packages`, `updated_releases`, `changed_packages`.
- Sometimes it returns Python Tracebacks as strings on the body of the response.


#### Notes

- https://chriswarrick.com/blog/2018/07/17/pipenv-promises-a-lot-delivers-very-little/
- https://old.reddit.com/r/Python/comments/chkah3/is_pipenv_dead_why_has_the_project_stopped/
- https://github.com/ofek/hatch
- https://github.com/sdispater/poetry
- https://github.com/pypa/pip/tree/master/src/pip/_internal/commands
- pipsi, pipx (Dead/Stalled projects?)
- http://pyfound.blogspot.com/2019/07/pypi-now-supports-uploading-via-api.html

> Release cadence came to a super dramatic halt because of a lot of upstream issues (pip broke, setuptools broke, then pip and setuptools both released breaking fixes, and we have about 15 upstream dependencies which I personally maintain)

-->
