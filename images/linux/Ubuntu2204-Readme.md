| Announcements |
|-|
| [[all OSs] Default Nodejs version will be set to 18 on February, 13](https://github.com/actions/runner-images/issues/7002) |
| [[All OSs] .NET 5.x will be removed from the images on February, 6](https://github.com/actions/runner-images/issues/6840) |
| [The Ubuntu 18.04 Actions runner image will begin deprecation on 2022/08/08 and will be fully unsupported by 2023/04/01](https://github.com/actions/runner-images/issues/6002) |
***
# Ubuntu 22.04
- OS Version: 22.04.1 LTS
- Kernel Version: 5.15.0-1031-azure
- Image Version: 20230129.2

## Installed Software

### Language and Runtime
- Bash 5.1.16(1)-release
- Clang: 12.0.1, 13.0.1, 14.0.0
- Clang-format: 12.0.1, 13.0.1, 14.0.0
- Clang-tidy: 12.0.1, 13.0.1, 14.0.0
- Dash 0.5.11+git20210903+057cd650a4ed-3build1
- GNU C++: 9.5.0, 10.4.0, 11.3.0, 12.1.0
- GNU Fortran: 9.5.0, 10.4.0, 11.3.0, 12.1.0
- Julia 1.8.5
- Kotlin 1.8.0-release-345
- Mono 6.12.0.182
- MSBuild 16.10.1.31701 (Mono 6.12.0.182)
- Node.js 16.19.0
- Perl 5.34.0
- Python 3.10.6
- Python3 3.10.6
- Ruby 3.0.2p107
- Swift 5.7.3

### Package Management
- cpan 1.64
- Helm 3.11.0
- Homebrew 3.6.20
- Miniconda 22.11.1
- Npm 8.19.3
- NuGet 6.3.1.1
- Pip 22.0.2
- Pip3 22.0.2
- Pipx 1.1.0
- RubyGems 3.3.5
- Vcpkg (build from commit 91dd61bd4)
- Yarn 1.22.19

#### Environment variables
| Name                    | Value                  |
| ----------------------- | ---------------------- |
| CONDA                   | /usr/share/miniconda   |
| VCPKG_INSTALLATION_ROOT | /usr/local/share/vcpkg |

#### Homebrew note
```
Location: /home/linuxbrew
Note: Homebrew is pre-installed on image but not added to PATH.
run the eval "$(/home/linuxbrew/.linuxbrew/bin/brew shellenv)" command
to accomplish this.
```

### Project Management
- Lerna 6.4.1

### Tools
- Ansible 2.14.1
- apt-fast 1.9.12
- AzCopy 10.17.0 - available by `azcopy` and `azcopy10` aliases
- Bazel 6.0.0
- Bazelisk 1.13.2
- Bicep 0.13.1
- Buildah 1.23.1
- CMake 3.25.2
- CodeQL Action Bundles 2.12.0 2.12.1
- Docker Amazon ECR Credential Helper 0.6.0
- Docker Compose v1 1.29.2
- Docker Compose v2 2.15.1+azure-1
- Docker-Buildx 0.10.0
- Docker-Moby Client 20.10.22+azure-1
- Docker-Moby Server 20.10.22+azure-1
- Fastlane 2.211.0
- Git 2.39.1
- Git LFS 3.3.0
- Git-ftp 1.6.0
- Haveged 1.9.14
- Heroku 7.67.2
- jq 1.6
- Kind 0.17.0
- Kubectl 1.26.1
- Kustomize 4.5.7
- Leiningen 2.10.0
- MediaInfo 21.09
- Mercurial 6.1.1
- Minikube 1.29.0
- n 9.0.1
- Newman 5.3.2
- nvm 0.39.3
- OpenSSL 3.0.2-0ubuntu1.7
- Packer 1.8.5
- Parcel 2.8.3
- Podman 3.4.4
- Pulumi 3.53.1
- R 4.2.2
- Skopeo 1.4.1
- Sphinx Open Source Search Server 2.2.11
- SVN 1.14.1
- Terraform 1.3.7
- yamllint 1.29.0
- yq 4.30.8
- zstd 1.5.2

### CLI Tools
- Alibaba Cloud CLI 3.0.144
- AWS CLI 2.9.19
- AWS CLI Session Manager Plugin 1.2.398.0
- AWS SAM CLI 1.71.0
- Azure CLI 2.44.1
- Azure CLI (azure-devops) 0.26.0
- GitHub CLI 2.22.1
- Google Cloud SDK 415.0.0
- Hub CLI 2.14.2
- Netlify CLI 12.10.0
- OpenShift CLI 4.12.0
- ORAS CLI 0.16.0
- Vercel CLI 28.14.0

### Java
| Version              | Vendor          | Environment Variable |
| -------------------- | --------------- | -------------------- |
| 8.0.362+9            | Eclipse Temurin | JAVA_HOME_8_X64      |
| 11.0.18+10 (default) | Eclipse Temurin | JAVA_HOME_11_X64     |
| 17.0.6+10            | Eclipse Temurin | JAVA_HOME_17_X64     |

### GraalVM
| Version   | Environment variables |
| --------- | --------------------- |
| CE 22.3.1 | GRAALVM_11_ROOT       |

### PHP Tools
- PHP: 8.1.2
- Composer 2.5.1
- PHPUnit 8.5.32
```
Both Xdebug and PCOV extensions are installed, but only Xdebug is enabled.
```

### Haskell Tools
- Cabal 3.6.2.0
- GHC 9.4.4
- GHCup 0.1.19.0
- Stack 2.9.3

### Rust Tools
- Cargo 1.67.0
- Rust 1.67.0
- Rustdoc 1.67.0
- Rustup 1.25.1

#### Packages
- Bindgen 0.63.0
- Cargo audit 0.17.4
- Cargo clippy 0.1.67
- Cargo outdated 0.11.2
- Cbindgen 0.24.3
- Rustfmt 1.5.1

### Browsers and Drivers
- Google Chrome 109.0.5414.119
- ChromeDriver 109.0.5414.74
- Chromium 109.0.5414.0
- Microsoft Edge 109.0.1518.70
- Microsoft Edge WebDriver 109.0.1518.70
- Selenium server 4.8.0
- Mozilla Firefox 109.0.1
- Geckodriver 0.32.0

#### Environment variables
| Name              | Value                               |
| ----------------- | ----------------------------------- |
| CHROMEWEBDRIVER   | /usr/local/share/chrome_driver      |
| EDGEWEBDRIVER     | /usr/local/share/edge_driver        |
| GECKOWEBDRIVER    | /usr/local/share/gecko_driver       |
| SELENIUM_JAR_PATH | /usr/share/java/selenium-server.jar |

### .NET Tools
- .NET Core SDK: 6.0.405, 7.0.102
- nbgv 3.5.119+5d25f54fec

### Databases
- sqlite3 3.37.2

#### PostgreSQL
- PostgreSQL 14.6
```
User: postgres
PostgreSQL service is disabled by default.
Use the following command as a part of your job to start the service: 'sudo systemctl start postgresql.service'
```

#### MySQL
- MySQL 8.0.32-0ubuntu0.22.04.2
```
User: root
Password: root
MySQL service is disabled by default.
Use the following command as a part of your job to start the service: 'sudo systemctl start mysql.service'
```

#### MS SQL
- sqlcmd 17.10.0001.1
- SqlPackage 16.1.6374.0

### Cached Tools

#### Go
- 1.17.13
- 1.18.10
- 1.19.5

#### Node.js
- 14.21.2
- 16.19.0
- 18.13.0

#### Python
- 3.7.15
- 3.8.16
- 3.9.16
- 3.10.9
- 3.11.1

#### PyPy
- 3.7.13 [PyPy 7.3.9]
- 3.8.16 [PyPy 7.3.11]
- 3.9.16 [PyPy 7.3.11]

#### Ruby
- 3.1.3

### PowerShell Tools
- PowerShell 7.2.9

#### PowerShell Modules
- Az: 9.3.0
- MarkdownPS: 1.9
- Microsoft.Graph: 1.20.0
- Pester: 5.4.0
- PSScriptAnalyzer: 1.21.0

### Web Servers
| Name    | Version | ConfigFile                | ServiceStatus | ListenPort |
| ------- | ------- | ------------------------- | ------------- | ---------- |
| apache2 | 2.4.52  | /etc/apache2/apache2.conf | inactive      | 80         |
| nginx   | 1.18.0  | /etc/nginx/nginx.conf     | inactive      | 80         |

### Android
| Package Name               | Version                                                                                                                                                                           |
| -------------------------- | --------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Android Command Line Tools | 9.0                                                                                                                                                                               |
| Android Emulator           | 31.3.14                                                                                                                                                                           |
| Android SDK Build-tools    | 33.0.0 33.0.1<br>32.0.0<br>31.0.0<br>30.0.0 30.0.1 30.0.2 30.0.3<br>29.0.0 29.0.1 29.0.2 29.0.3<br>28.0.0 28.0.1 28.0.2 28.0.3<br>27.0.0 27.0.1 27.0.2 27.0.3                     |
| Android SDK Platform-Tools | 33.0.3                                                                                                                                                                            |
| Android SDK Platforms      | android-33-ext4 (rev 1)<br>android-33 (rev 2)<br>android-32 (rev 1)<br>android-31 (rev 1)<br>android-30 (rev 3)<br>android-29 (rev 5)<br>android-28 (rev 6)<br>android-27 (rev 3) |
| Android SDK Tools          | 26.1.1                                                                                                                                                                            |
| Android Support Repository | 47.0.0                                                                                                                                                                            |
| CMake                      | 3.10.2<br>3.18.1<br>3.22.1                                                                                                                                                        |
| Google Play services       | 49                                                                                                                                                                                |
| Google Repository          | 58                                                                                                                                                                                |
| NDK                        | 23.2.8568313<br>24.0.8215888<br>25.1.8937393 (default)                                                                                                                            |
| SDK Patch Applier v4       | 1                                                                                                                                                                                 |

#### Environment variables
| Name                    | Value                                       |
| ----------------------- | ------------------------------------------- |
| ANDROID_HOME            | /usr/local/lib/android/sdk                  |
| ANDROID_NDK             | /usr/local/lib/android/sdk/ndk/25.1.8937393 |
| ANDROID_NDK_HOME        | /usr/local/lib/android/sdk/ndk/25.1.8937393 |
| ANDROID_NDK_LATEST_HOME | /usr/local/lib/android/sdk/ndk/25.1.8937393 |
| ANDROID_NDK_ROOT        | /usr/local/lib/android/sdk/ndk/25.1.8937393 |
| ANDROID_SDK_ROOT        | /usr/local/lib/android/sdk                  |

### Cached Docker images
| Repository:Tag          | Digest                                                                   | Created    |
| ----------------------- | ------------------------------------------------------------------------ | ---------- |
| alpine:3.14             | sha256:4c869a63e1b7c0722fed1e402a6466610327c3b83bdddb94bd94fb71da7f638a  | 2022-08-09 |
| alpine:3.15             | sha256:cf34c62ee8eb3fe8aa24c1fab45d7e9d12768d945c3f5a6fd6a63d901e898479  | 2022-08-09 |
| alpine:3.16             | sha256:b95359c2505145f16c6aa384f9cc74eeff78eb36d308ca4fd902eeeb0a0b161b  | 2022-11-12 |
| buildpack-deps:bullseye | sha256:c1a2475ac14e13582cf8a44fc071439132928ada47c57e80af372fdcd1690751  | 2023-01-11 |
| buildpack-deps:buster   | sha256:c343da4a0b85a4d25ce30529e836a10d46cd4f682fb5326400e4ba274a2f9866  | 2023-01-11 |
| debian:10               | sha256:bb8c62f9f540a5f5f49f7ed5caae0e2889f999cd14553f2aaccaf1fa4fcb998d  | 2023-01-11 |
| debian:11               | sha256:534da5794e770279c889daa891f46f5a530b0c5de8bfbc5e40394a0164d9fa87  | 2023-01-11 |
| moby/buildkit:latest    | sha256:f092403997f04742b549811ca2402d88207afbf33656eb1cf34aa7fe8a8511ac  | 2023-01-26 |
| node:14                 | sha256:0c888dc647d36f5a895edb6b1b1c96ae81064455e0cdeee0792e14927604ca99  | 2023-01-11 |
| node:14-alpine          | sha256:2c6a909495ef3761328c10945cbe84c06d079f7ca49dc24271e73be8cab85ad7  | 2023-01-09 |
| node:16                 | sha256:27fab5920246070cf13449cf44c25bc4f5adef18ca7482b2bda90b7cf9e64481  | 2023-01-11 |
| node:16-alpine          | sha256:1298fd170c45954fec3d4d063437750f89802d72743816663664cfe9aa152b4b  | 2023-01-09 |
| node:18                 | sha256:d871edd5b68105ebcbfcde3fe8c79d24cbdbb30430d9bd6251c57c56c7bd7646  | 2023-01-11 |
| node:18-alpine          | sha256:fda98168118e5a8f4269efca4101ee51dd5c75c0fe56d8eb6fad80455c2f5827  | 2023-01-09 |
| ubuntu:18.04            | sha256:c1d0baf2425ecef88a2f0c3543ec43690dc16cc80d3c4e593bb95e4f45390e45  | 2023-01-02 |
| ubuntu:20.04            | sha256:0e0402cd13f68137edb0266e1d2c682f217814420f2d43d300ed8f65479b14fb  | 2022-12-09 |
| ubuntu:22.04            | sha256:27cb6e6ccef575a4698b66f5de06c7ecd61589132d5a91d098f7f3f9285415a9  | 2022-12-09 |

### Installed apt packages
| Name                   | Version                           |
| ---------------------- | --------------------------------- |
| acl                    | 2.3.1-1                           |
| aria2                  | 1.36.0-1                          |
| autoconf               | 2.71-2                            |
| automake               | 1:1.16.5-1.3                      |
| binutils               | 2.38-4ubuntu2.1                   |
| bison                  | 2:3.8.2+dfsg-1build1              |
| brotli                 | 1.0.9-2build6                     |
| build-essential        | 12.9ubuntu3                       |
| bzip2                  | 1.0.8-5build1                     |
| coreutils              | 8.32-4.1ubuntu1                   |
| curl                   | 7.81.0-1ubuntu1.7                 |
| dbus                   | 1.12.20-2ubuntu4.1                |
| dnsutils               | 1:9.18.1-1ubuntu1.3               |
| dpkg                   | 1.21.1ubuntu2.1                   |
| fakeroot               | 1.28-1ubuntu1                     |
| file                   | 1:5.41-3                          |
| flex                   | 2.6.4-8build2                     |
| fonts-noto-color-emoji | 2.034-1                           |
| ftp                    | 20210827-4build1                  |
| gnupg2                 | 2.2.27-3ubuntu2.1                 |
| haveged                | 1.9.14-1ubuntu1                   |
| imagemagick            | 8:6.9.11.60+dfsg-1.3build2        |
| iproute2               | 5.15.0-1ubuntu2                   |
| iputils-ping           | 3:20211215-1                      |
| jq                     | 1.6-2.1ubuntu3                    |
| lib32z1                | 1:1.2.11.dfsg-2ubuntu9.2          |
| libc++-dev             | 1:14.0-55\~exp2                   |
| libc++abi-dev          | 1:14.0-55\~exp2                   |
| libcurl4               | 7.81.0-1ubuntu1.7                 |
| libgbm-dev             | 22.0.5-0ubuntu0.3                 |
| libgconf-2-4           | 3.2.6-7ubuntu2                    |
| libgsl-dev             | 2.7.1+dfsg-3                      |
| libgtk-3-0             | 3.24.33-1ubuntu2                  |
| libmagic-dev           | 1:5.41-3                          |
| libmagickcore-dev      | 8:6.9.11.60+dfsg-1.3build2        |
| libmagickwand-dev      | 8:6.9.11.60+dfsg-1.3build2        |
| libsecret-1-dev        | 0.20.5-2                          |
| libsqlite3-dev         | 3.37.2-2ubuntu0.1                 |
| libssl-dev             | 3.0.2-0ubuntu1.7                  |
| libtool                | 2.4.6-15build2                    |
| libunwind8             | 1.3.2-2build2                     |
| libxkbfile-dev         | 1:1.1.0-1build3                   |
| libxss1                | 1:1.2.3-1build2                   |
| libyaml-dev            | 0.2.2-1build2                     |
| locales                | 2.35-0ubuntu3.1                   |
| lz4                    | 1.9.3-2build2                     |
| m4                     | 1.4.18-5ubuntu2                   |
| mediainfo              | 22.03-1                           |
| mercurial              | 6.1.1-1ubuntu1                    |
| net-tools              | 1.60+git20181103.0eebece-1ubuntu5 |
| netcat                 | 1.218-4ubuntu1                    |
| openssh-client         | 1:8.9p1-3ubuntu0.1                |
| p7zip-full             | 16.02+dfsg-8                      |
| p7zip-rar              | 16.02-3build1                     |
| parallel               | 20210822+ds-2                     |
| pass                   | 1.7.4-5                           |
| patchelf               | 0.14.3-1                          |
| pkg-config             | 0.29.2-1ubuntu3                   |
| pollinate              | 4.33-3ubuntu2                     |
| python-is-python3      | 3.9.2-2                           |
| rpm                    | 4.17.0+dfsg1-4build1              |
| rsync                  | 3.2.3-8ubuntu3.1                  |
| shellcheck             | 0.8.0-2                           |
| sphinxsearch           | 2.2.11-8                          |
| sqlite3                | 3.37.2-2ubuntu0.1                 |
| ssh                    | 1:8.9p1-3ubuntu0.1                |
| sshpass                | 1.09-1                            |
| subversion             | 1.14.1-3ubuntu0.22.04.1           |
| sudo                   | 1.9.9-1ubuntu2.2                  |
| swig                   | 4.0.2-1ubuntu1                    |
| tar                    | 1.34+dfsg-1build3                 |
| telnet                 | 0.17-44build1                     |
| texinfo                | 6.8-4build1                       |
| time                   | 1.9-0.1build2                     |
| tk                     | 8.6.11+1build2                    |
| tzdata                 | 2022g-0ubuntu0.22.04.1            |
| unzip                  | 6.0-26ubuntu3.1                   |
| upx                    | 3.96-3                            |
| wget                   | 1.21.2-2ubuntu1                   |
| xorriso                | 1.5.4-2                           |
| xvfb                   | 2:21.1.3-2ubuntu2.5               |
| xz-utils               | 5.2.5-2ubuntu1                    |
| zip                    | 3.0-12build2                      |
| zsync                  | 0.6.2-3ubuntu1                    |

