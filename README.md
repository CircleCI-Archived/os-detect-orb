# OS Detect Orb [![CircleCI Build Status](https://circleci.com/gh/CircleCI-Public/os-detect-orb.svg?style=shield "CircleCI Build Status")](https://circleci.com/gh/CircleCI-Public/os-detect-orb) [![CircleCI Orb Version](https://img.shields.io/badge/endpoint.svg?url=https://badges.circleci.io/orb/circleci/os-detect)][reg-page] [![GitHub License](https://img.shields.io/badge/license-MIT-lightgrey.svg)](https://raw.githubusercontent.com/CircleCI-Public/os-detect-orb/master/LICENSE)

An orb to make it easy to detect which operating system (OS) and version your orb and/or CircleCI config is running on.

CircleCI Support

| Executor/OS    | Supported? | Shell |
|---             |---         |---    |
| Docker/Ubuntu  | yes        | Bash  |
| Docker/Debian  | yes        | Bash  |
| Docker/Alpine  | yes        | Bash  |
| macOS          | yes        | Bash  |
| machine/Ubuntu | yes        | Bash  |


## Usage

Example use as well as a list of available executors, commands, and jobs are available on this orb's [registry page][reg-page].

| Variables     | Description |
|---            |---          |
| $OSD_FAMILY   | The OS family. For example, linux or darwin
| $OSD_ID       | The OS slug name. For example, ubuntu, alpine or macos.
| $OSD_VERSION  | The OS version number, as advertised. For example, 18.04 for Ubuntu or 10.9 for macOS.
| $SUDO         | Contains the string "sudo" when the current user is not root and the `sudo` binary is available. Prefix this with your commands.


## Resources

[CircleCI Orb Registry Page][reg-page] - The official registry page for this orb will include all versions, executors, commands, and have described the jobs.  
[CircleCI Orb Docs](https://circleci.com/docs/2.0/orb-intro/#section=configuration) - Docs for using and creating CircleCI Orbs.  


## Contributing
We welcome [issues](https://github.com/CircleCI-Public/os-detect-orb/issues) to and [pull requests](https://github.com/CircleCI-Public/os-detect-orb/pulls) against this repository!
For further questions/comments about this or other orbs, visit the Orb Category of [CircleCI Discuss](https://discuss.circleci.com/c/orbs).

### Publishing

New versions of this orb are published by pushing a SemVer git tag by the Community & Partner Engineering Team.

## License
This project is licensed under the MIT License - read [LICENSE](LICENSE) file for details.

[reg-page]: https://circleci.com/orbs/registry/orb/circleci/orb-detect
