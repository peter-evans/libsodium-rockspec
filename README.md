# LuaRocks rock for the Sodium Crypto Library (libsodium)
[![luarocks](https://img.shields.io/badge/luarocks-libsodium-blue.svg)](https://luarocks.org/modules/peterevans/libsodium)
[![Build Status](https://travis-ci.org/peter-evans/libsodium-rockspec.svg?branch=master)](https://travis-ci.org/peter-evans/libsodium-rockspec)

This is a convenient way to install the [Sodium Crypto Library (libsodium)](https://github.com/jedisct1/libsodium) via LuaRocks.

I don't necessarily recommend this for production use. Please see [libsodium's documentation](https://download.libsodium.org/doc/installation/) for full installation instructions.

**Please note this is not a libsodium to Lua binding! It just installs libsodium.**

## Installation

```
luarocks install libsodium
```

Check if libsodium has installed correctly:
```
pkg-config --libs libsodium
```

## License

MIT License - see the [LICENSE](LICENSE) file for details
