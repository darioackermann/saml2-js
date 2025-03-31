# 7.1.0

### Features
* Return Assertion ID as part of the user object (see #25)

### Chores
* Add test case for `xmldorm.parse` failing in post_assert
* Addresses a deprecation notice regarding `Buffer` in tests
* Dependencies updated

# 7.0.0

### Breaking changes
* The parser of xmldom is now stricter before, please verify that your SAML assertions are conforming, see [its changelog](https://github.com/xmldom/xmldom/blob/master/CHANGELOG.md#090-beta9). 
* Supported node versions are now `^18.18.0 || ^20.9.0 || >=21.1.0` (required by mocha)

### Changes

* Updates xmldom to `0.9.7` and needed adjustments of libary and tests, kudos to @martinslota 🎉 
* Updates mocha to `11.0.1`  (@darioackermann) 

# 6.0.0

**Breaking change**: Node >= 18 is required now.

- chore: Update ncy to ^17.0.0

# 5.0.0

- **Breaking change**: Only Node >= 16 supported due to dependency updates
- chores: Dependency updates and internal changes due to changed apis
