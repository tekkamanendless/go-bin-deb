# Changelog - go-bin-deb

### 0.0.19

__Changes__

- close #3: document tokens
- close #5: ensure an empty changelog file exits in the dest package
- demo: update
- dev: code review, bump script

__Contributors__

- mh-cbon

Released by mh-cbon, Thu 24 Aug 2017 -
[see the diff](https://github.com/tekkamanendless/go-bin-deb/compare/0.0.19-beta...0.0.19#diff)
______________

### 0.0.19-beta

__Changes__

- support: updated all support script
- release: repo setup: remove dlded packages
- travis: update deploy token

__Contributors__

- mh-cbon

Released by mh-cbon, Thu 20 Apr 2017 -
[see the diff](https://github.com/tekkamanendless/go-bin-deb/compare/0.0.18...0.0.19-beta#diff)
______________

### 0.0.18

__Changes__

- support: updated all support script
- go vet
- fix apt repository

__Contributors__

- mh-cbon

Released by mh-cbon, Tue 18 Apr 2017 -
[see the diff](https://github.com/tekkamanendless/go-bin-deb/compare/0.0.17...0.0.18#diff)
______________

### 0.0.17

__Changes__

- support: updated all support script
- deploy: update helper script to generate repo source to ensure GH_TOKEN is not empty
- release script: create-release add changelog support, add draft support

__Contributors__

- mh-cbon

Released by mh-cbon, Tue 18 Apr 2017 -
[see the diff](https://github.com/tekkamanendless/go-bin-deb/compare/0.0.16...0.0.17#diff)
______________

### 0.0.16

__Changes__

- travis: update build file, add deb/rpm repositories setup
- source repository: use token when downloading assets
- souce repository: use aptly to create the repo
- souce repository: use aptly to create the repo
- support: add centralized script to generate packages and repository
- packaging: remove changelog urgency var in deb.json
- README: add workflow overview section
- README: Fix missing changelog setup in travis sample

__Contributors__

- mh-cbon

Released by mh-cbon, Sat 30 Jul 2016 -
[see the diff](https://github.com/tekkamanendless/go-bin-deb/compare/0.0.15...0.0.16#diff)
______________

### 0.0.15

__Changes__

- README: add recipe for vagrant
- README: Add recipe to test the demo package on vagrant
- Installer: applied some improvements
- README: clean up
- travis: Install changelog from deb package
- git: update ignored files
- deb.json: make use of the new name token
- debian/: add new token \!name\!

__Contributors__

- mh-cbon

Released by mh-cbon, Mon 11 Jul 2016 -
[see the diff](https://github.com/tekkamanendless/go-bin-deb/compare/0.0.14...0.0.15#diff)
______________

### 0.0.14

__Changes__

- travis: add missing ldflags to the build

__Contributors__

- mh-cbon

Released by mh-cbon, Mon 11 Jul 2016 -
[see the diff](https://github.com/tekkamanendless/go-bin-deb/compare/0.0.13...0.0.14#diff)
______________

### 0.0.13

__Changes__

- conffiles is not created if there is no configuration files,
  ensure correct debian arch when control.arch field is 386






























__Contributors__

- mh-cbon

Released by mh-cbon, Mon 11 Jul 2016 -
[see the diff](https://github.com/tekkamanendless/go-bin-deb/compare/0.0.12...0.0.13#diff)
______________

### 0.0.12

__Changes__

- Ensure package are built into different directories and avoid collision

__Contributors__

- mh-cbon

Released by mh-cbon, Mon 11 Jul 2016 -
[see the diff](https://github.com/tekkamanendless/go-bin-deb/compare/0.0.11...0.0.12#diff)
______________

### 0.0.11

__Changes__

- run changelog command into source folder of the  project

__Contributors__

- mh-cbon

Released by mh-cbon, Mon 11 Jul 2016 -
[see the diff](https://github.com/tekkamanendless/go-bin-deb/compare/0.0.10...0.0.11#diff)
______________

### 0.0.10

__Changes__

- travis: fix go install

__Contributors__

- mh-cbon

Released by mh-cbon, Mon 11 Jul 2016 -
[see the diff](https://github.com/tekkamanendless/go-bin-deb/compare/0.0.9...0.0.10#diff)
______________

### 0.0.9

__Changes__

- travis: fix go install

__Contributors__

- mh-cbon

Released by mh-cbon, Mon 11 Jul 2016 -
[see the diff](https://github.com/tekkamanendless/go-bin-deb/compare/0.0.8...0.0.9#diff)
______________

### 0.0.8

__Changes__

- travis: fix path

__Contributors__

- mh-cbon

Released by mh-cbon, Mon 11 Jul 2016 -
[see the diff](https://github.com/tekkamanendless/go-bin-deb/compare/0.0.7...0.0.8#diff)
______________

### 0.0.7

__Changes__

- travis was missing changelog bin

__Contributors__

- mh-cbon

Released by mh-cbon, Mon 11 Jul 2016 -
[see the diff](https://github.com/tekkamanendless/go-bin-deb/compare/0.0.6...0.0.7#diff)
______________

### 0.0.6

__Changes__

- fix os/exec: stdout already set

__Contributors__

- mh-cbon

Released by mh-cbon, Mon 11 Jul 2016 -
[see the diff](https://github.com/tekkamanendless/go-bin-deb/compare/0.0.5...0.0.6#diff)
______________

### 0.0.5

__Changes__

- fix travis

__Contributors__

- mh-cbon

Released by mh-cbon, Mon 11 Jul 2016 -
[see the diff](https://github.com/tekkamanendless/go-bin-deb/compare/0.0.4...0.0.5#diff)
______________

### 0.0.4

__Changes__

- fix travis

__Contributors__

- mh-cbon

Released by mh-cbon, Mon 11 Jul 2016 -
[see the diff](https://github.com/tekkamanendless/go-bin-deb/compare/0.0.3...0.0.4#diff)
______________

### 0.0.3

__Changes__

- fix travis

__Contributors__

- mh-cbon

Released by mh-cbon, Mon 11 Jul 2016 -
[see the diff](https://github.com/tekkamanendless/go-bin-deb/compare/0.0.2...0.0.3#diff)
______________

### 0.0.2

__Changes__

- fix various glide problems
- fix missing vars to create MD changelog file

__Contributors__

- mh-cbon

Released by mh-cbon, Mon 11 Jul 2016 -
[see the diff](https://github.com/tekkamanendless/go-bin-deb/compare/0.0.1...0.0.2#diff)
______________

### 0.0.1

__Changes__

- Initial release

__Contributors__

- mh-cbon

Released by mh-cbon, Mon 11 Jul 2016 -
[see the diff](https://github.com/tekkamanendless/go-bin-deb/compare/aa86544bec0aab4238f0b216369545c0a3bcdcfe...0.0.1#diff)
______________


