| Announcements |
|-|
| [(Public Beta) Ubuntu 22.04 is now available](https://github.com/actions/virtual-environments/issues/5490) |
***
# Ubuntu 18.04.6 LTS
- Linux kernel version: 5.4.0-1085-azure
- Image Version: 20220626.1

## Installed Software
### Language and Runtime
- Bash 4.4.20(1)-release
- Clang 9.0.0
- Clang-format 9.0.0
- Clang-tidy 9.0.0
- Dash 0.5.8-2.10
- Erlang 25.0.2 (Eshell 13.0.2)
- Erlang rebar3 3.19.0
- GNU C++ 7.5.0, 9.4.0, 10.3.0
- GNU Fortran 7.5.0, 9.4.0, 10.3.0
- Julia 1.7.3
- Kotlin 1.7.0-release-281
- Mono 6.12.0.182 (apt source repository: https://download.mono-project.com/repo/ubuntu stable-bionic main)
- MSBuild 16.10.1.31701 (from /usr/lib/mono/msbuild/15.0/bin/MSBuild.dll)
- Node 16.15.1
- Perl 5.26.1
- Python 2.7.17
- Python3 3.6.9
- Ruby 2.5.1p57
- Swift 5.6.2

### Package Management
- cpan 1.64
- Helm 3.9.0
- Homebrew 3.5.2
- Miniconda 4.12.0
- Npm 8.11.0
- Pip 9.0.1
- Pip3 9.0.1
- Pipx 1.0.0
- RubyGems 2.7.6
- Vcpkg  (build from master \<c168ce4e7>)
- Yarn 1.22.19

#### Environment variables
| Name                    | Value                  |
| ----------------------- | ---------------------- |
| CONDA                   | /usr/share/miniconda   |
| VCPKG_INSTALLATION_ROOT | /usr/local/share/vcpkg |

### Project Management
- Ant 1.10.5
- Gradle 7.4.2
- Maven 3.8.6
- Sbt 1.6.2

### Tools
- Ansible 2.11.12
- apt-fast 1.9.12
- AzCopy 10.15.0 (available by `azcopy` and `azcopy10` aliases)
- Bazel 5.2.0
- Bazelisk 1.12.0
- Bicep 0.7.4
- Buildah 1.22.3 (apt source repository: https://download.opensuse.org/repositories/devel:/kubic:/libcontainers:/stable)
- CMake 3.23.2
- CodeQL Action Bundle 2.9.4
- Docker Amazon ECR Credential Helper 0.6.0
- Docker Compose v1 1.29.2
- Docker Compose v2 2.6.0+azure-1
- Docker-Buildx 0.8.2
- Docker-Moby Client 20.10.17+azure-1
- Docker-Moby Server 20.10.17+azure-1
- Git 2.36.1 (apt source repository: ppa:git-core/ppa)
- Git LFS 3.2.0 (apt source repository: https://packagecloud.io/install/repositories/github/git-lfs)
- Git-ftp 1.3.1
- Haveged 1.9.1
- Heroku 7.60.2
- HHVM (HipHop VM) 4.163.0
- jq 1.5
- Kind 0.14.0
- Kubectl 1.24.2
- Kustomize 4.5.5
- Leiningen 2.9.8
- MediaInfo 17.12
- Mercurial 4.5.3
- Minikube 1.26.0
- n 8.2.0
- Newman 5.3.2
- nvm 0.39.1
- OpenSSL 1.1.1-1ubuntu2.1~18.04.19
- Packer 1.8.2
- Parcel 2.6.2
- PhantomJS 2.1.1
- Podman 3.4.2 (apt source repository: https://download.opensuse.org/repositories/devel:/kubic:/libcontainers:/stable)
- Pulumi 3.35.1
- R 4.2.0
- Skopeo 1.5.0 (apt source repository: https://download.opensuse.org/repositories/devel:/kubic:/libcontainers:/stable)
- Sphinx Open Source Search Server 2.2.11
- SVN 1.9.7
- Terraform 1.2.3
- yamllint 1.26.3
- yq 4.25.3
- zstd 1.5.2 (homebrew)

### CLI Tools
- Alibaba Cloud CLI 3.0.124
- AWS CLI 2.7.11
- AWS CLI Session manager plugin 1.2.339.0
- AWS SAM CLI 1.52.0
- Azure CLI (azure-cli) 2.37.0 (installation method: https://docs.microsoft.com/en-us/cli/azure/install-azure-cli-linux?pivots=apt)
- Azure CLI (azure-devops) 0.25.0
- GitHub CLI 2.13.0
- Google Cloud SDK 369.0.0 (apt source repository: https://packages.cloud.google.com/apt)
- Hub CLI 2.14.2
- Netlify CLI 10.6.2
- OpenShift CLI 4.10.18
- ORAS CLI 0.12.0
- Vercel CLI 25.1.0

### Java
| Version             | Vendor          | Environment Variable |
| ------------------- | --------------- | -------------------- |
| 8.0.332+9 (default) | Eclipse Temurin | JAVA_HOME_8_X64      |
| 11.0.15+10          | Eclipse Temurin | JAVA_HOME_11_X64     |
| 12.0.2+10           | Adopt OpenJDK   | JAVA_HOME_12_X64     |
| 17.0.3+7            | Eclipse Temurin | JAVA_HOME_17_X64     |

### PHP
| Tool     | Version                           |
| -------- | --------------------------------- |
| PHP      | 7.2.34 7.3.33 7.4.30 8.0.20 8.1.7 |
| Composer | 2.3.7                             |
| PHPUnit  | 8.5.27                            |
```
    Both Xdebug and PCOV extensions are installed, but only Xdebug is enabled.
```
### Haskell
- Cabal 3.6.2.0
- GHC 9.2.3
- GHCup 0.1.17.8
- Stack 2.7.5

### Rust Tools
- Cargo 1.61.0
- Rust 1.61.0
- Rustdoc 1.61.0
- Rustup 1.24.3

#### Packages
- Bindgen 0.60.1
- Cargo audit 0.17.0
- Cargo clippy 0.1.61
- Cargo outdated 0.11.1
- Cbindgen 0.24.3
- Rustfmt 1.4.38

### Browsers and Drivers
- Google Chrome 103.0.5060.53
- ChromeDriver 103.0.5060.53
- Chromium 103.0.5060.0
- Selenium server 4.3.0
- Mozilla Firefox 101.0.1
- Geckodriver 0.31.0

#### Environment variables
| Name              | Value                               |
| ----------------- | ----------------------------------- |
| CHROMEWEBDRIVER   | /usr/local/share/chrome_driver      |
| GECKOWEBDRIVER    | /usr/local/share/gecko_driver       |
| SELENIUM_JAR_PATH | /usr/share/java/selenium-server.jar |

### .NET Core SDK
- 3.1.120 3.1.202 3.1.302 3.1.420 5.0.104 5.0.214 5.0.303 5.0.408 6.0.301

### .NET tools
- nbgv 3.5.107+6463ef6068

### Databases
- MongoDB 5.0.9 (apt source repository: https://repo.mongodb.org/apt/ubuntu)
- sqlite3 3.22.0

#### PostgreSQL
- PostgreSQL 14.4 (apt source repository: https://apt.postgresql.org/pub/repos/apt/)
- PostgreSQL Server (user:postgres)

```
    PostgreSQL service is disabled by default. Use the following command as a part of your job to start the service: 'sudo systemctl start postgresql.service'
```
#### MySQL
- MySQL 5.7.38
- MySQL Server (user:root password:root)

```
    MySQL service is disabled by default. Use the following command as a part of your job to start the service: 'sudo systemctl start mysql.service'
```
#### MS SQL Server Client Tools
- sqlcmd 17.9.0001.1
- SqlPackage 16.0.6161.0

### Cached Tools
#### Go
- 1.16.15
- 1.17.11
- 1.18.3

#### Node.js
- 12.22.12
- 14.19.3
- 16.15.1

#### PyPy
- 2.7.18 [PyPy 7.3.9]
- 3.6.12 [PyPy 7.3.3]
- 3.9.12 [PyPy 7.3.9]

#### Python
- 2.7.18
- 3.6.15
- 3.7.13
- 3.8.13
- 3.9.13
- 3.10.5

#### Ruby
- 2.4.10
- 2.5.9
- 2.6.10
- 2.7.6
- 3.0.4
- 3.1.2

#### Environment variables
| Name            | Value                               | Architecture |
| --------------- | ----------------------------------- | ------------ |
| GOROOT_1_16_X64 | /opt/hostedtoolcache/go/1.16.15/x64 | x64          |
| GOROOT_1_17_X64 | /opt/hostedtoolcache/go/1.17.11/x64 | x64          |
| GOROOT_1_18_X64 | /opt/hostedtoolcache/go/1.18.3/x64  | x64          |

### PowerShell Tools
- PowerShell 7.2.5

#### PowerShell Modules
| Module          | Version |
| --------------- | ------- |
| MarkdownPS      | 1.9     |
| Microsoft.Graph | 1.10.0  |
| Pester          | 5.3.3   |

#### Az PowerShell Modules
- 7.3.2 3.1.0.zip 4.4.0.zip 5.9.0.zip 6.6.0.zip

### Web Servers
| Name    | Version | ConfigFile                | ServiceStatus | ListenPort |
| ------- | ------- | ------------------------- | ------------- | ---------- |
| apache2 | 2.4.29  | /etc/apache2/apache2.conf | inactive      | 80         |
| nginx   | 1.14.0  | /etc/nginx/nginx.conf     | inactive      | 80         |

### Android
| Package Name               | Version                                                                                                                                                                                                                                                                     |
| -------------------------- | --------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Android Command Line Tools | 7.0                                                                                                                                                                                                                                                                         |
| Android Emulator           | 31.2.10                                                                                                                                                                                                                                                                     |
| Android SDK Build-tools    | 33.0.0<br>32.0.0<br>31.0.0<br>30.0.0 30.0.1 30.0.2 30.0.3<br>29.0.0 29.0.1 29.0.2 29.0.3<br>28.0.0 28.0.1 28.0.2 28.0.3<br>27.0.0 27.0.1 27.0.2 27.0.3<br>26.0.0 26.0.1 26.0.2 26.0.3<br>25.0.0 25.0.1 25.0.2 25.0.3<br>24.0.0 24.0.1 24.0.2 24.0.3<br>23.0.1 23.0.2 23.0.3 |
| Android SDK Platform-Tools | 33.0.2                                                                                                                                                                                                                                                                      |
| Android SDK Platforms      | android-33 (rev 1)<br>android-32 (rev 1)<br>android-31 (rev 1)<br>android-30 (rev 3)<br>android-29 (rev 5)<br>android-28 (rev 6)<br>android-27 (rev 3)<br>android-26 (rev 2)<br>android-25 (rev 3)<br>android-24 (rev 2)<br>android-23 (rev 3)                              |
| Android SDK Tools          | 26.1.1                                                                                                                                                                                                                                                                      |
| Android Support Repository | 47.0.0                                                                                                                                                                                                                                                                      |
| CMake                      | 3.10.2<br>3.18.1                                                                                                                                                                                                                                                            |
| Google APIs                | addon-google_apis-google-21<br>addon-google_apis-google-22<br>addon-google_apis-google-23<br>addon-google_apis-google-24                                                                                                                                                    |
| Google Play services       | 49                                                                                                                                                                                                                                                                          |
| Google Repository          | 58                                                                                                                                                                                                                                                                          |
| NDK                        | 21.4.7075529<br>23.2.8568313 (default)<br>24.0.8215888                                                                                                                                                                                                                      |
| SDK Patch Applier v4       | 1                                                                                                                                                                                                                                                                           |

#### Environment variables
| Name                    | Value                                                                                |
| ----------------------- | ------------------------------------------------------------------------------------ |
| ANDROID_HOME            | /usr/local/lib/android/sdk                                                           |
| ANDROID_NDK_HOME        | /usr/local/lib/android/sdk/ndk-bundle -> /usr/local/lib/android/sdk/ndk/23.2.8568313 |
| ANDROID_NDK_LATEST_HOME | /usr/local/lib/android/sdk/ndk/24.0.8215888                                          |
| ANDROID_NDK_ROOT        | /usr/local/lib/android/sdk/ndk-bundle -> /usr/local/lib/android/sdk/ndk/23.2.8568313 |
| ANDROID_SDK_ROOT        | /usr/local/lib/android/sdk                                                           |

### Cached Docker images
| Repository:Tag          | Digest                                                                   | Created    |
| ----------------------- | ------------------------------------------------------------------------ | ---------- |
| alpine:3.12             | sha256:c75ac27b49326926b803b9ed43bf088bc220d22556de1bc5f72d742c91398f69  | 2022-04-05 |
| alpine:3.13             | sha256:ccf92aa53bc6c3b25be2ad0cce80baec1778f007f7e076b0ffbd1b225d0b3a9b  | 2022-04-05 |
| alpine:3.14             | sha256:06b5d462c92fc39303e6363c65e074559f8d6b1363250027ed5053557e3398c5  | 2022-04-05 |
| buildpack-deps:bullseye | sha256:7a78a5f716dd32b0eb89876f8c5cf5e443781a44b7fe12619e897bad9a642e14  | 2022-06-23 |
| buildpack-deps:buster   | sha256:7f9a157d07e0a81a4e3130ce1490142b208155e09d1c3459b4213a5779e87546  | 2022-06-23 |
| buildpack-deps:stretch  | sha256:78e995165a5788c2f55aed6e548d8f6c1534830d4310c870408fccb2da8c5b2e  | 2022-06-23 |
| debian:10               | sha256:9740683722a2a8aa497a5b23e4bc229fcf8b8991e26d3935540c7704ff24012e  | 2022-06-23 |
| debian:11               | sha256:859ea45db307402ee024b153c7a63ad4888eb4751921abbef68679fc73c4c739  | 2022-06-23 |
| debian:9                | sha256:c5c5200ff1e9c73ffbf188b4a67eb1c91531b644856b4aefe86a58d2f0cb05be  | 2022-06-23 |
| moby/buildkit:latest    | sha256:0dc312b04eac1b44cd2cad566deb1e886c753109208affbbec8384f381ff7f38  | 2022-05-06 |
| node:12                 | sha256:01627afeb110b3054ba4a1405541ca095c8bfca1cb6f2be9479c767a2711879e  | 2022-04-20 |
| node:12-alpine          | sha256:d4b15b3d48f42059a15bd659be60afe21762aae9d6cbea6f124440895c27db68  | 2022-04-11 |
| node:14                 | sha256:ce156f9b2e9dbe73139cf0619a71188960e6c9eaba0ff832a5dfa0febf9eee27  | 2022-06-23 |
| node:14-alpine          | sha256:6b87d16e4ce20cacd6f1f662f66c821e4c3c41c2903daeace52d818ec3f4bbdd  | 2022-06-07 |
| node:16                 | sha256:a13d2d2aec7f0dae18a52ca4d38b592e45a45cc4456ffab82e5ff10d8a53d042  | 2022-06-23 |
| node:16-alpine          | sha256:c785e617c8d7015190c0d41af52cc69be8a16e3d9eb7cb21f0bb58bcfca14d6b  | 2022-06-07 |
| ubuntu:16.04            | sha256:20858ebbc96215d6c3c574f781133ebffdc7c18d98af4f294cc4c04871a6fe61  | 2021-08-31 |
| ubuntu:18.04            | sha256:478caf1bec1afd54a58435ec681c8755883b7eb843a8630091890130b15a79af  | 2022-06-06 |
| ubuntu:20.04            | sha256:fd92c36d3cb9b1d027c4d2a72c6bf0125da82425fc2ca37c414d4f010180dc19  | 2022-06-06 |

### Installed apt packages
| Name              | Version                           |
| ----------------- | --------------------------------- |
| aria2             | 1.33.1-1                          |
| autoconf          | 2.69-11                           |
| automake          | 1:1.15.1-3ubuntu2                 |
| binutils          | 2.30-21ubuntu1\~18.04.7           |
| bison             | 2:3.0.4.dfsg-1build1              |
| brotli            | 1.0.3-1ubuntu1.3                  |
| build-essential   | 12.4ubuntu1                       |
| bzip2             | 1.0.6-8.1ubuntu0.2                |
| coreutils         | 8.28-1ubuntu1                     |
| curl              | 7.58.0-2ubuntu3.18                |
| dbus              | 1.12.2-1ubuntu1.3                 |
| dnsutils          | 1:9.11.3+dfsg-1ubuntu1.17         |
| dpkg              | 1.19.0.5ubuntu2.4                 |
| fakeroot          | 1.22-2ubuntu1                     |
| file              | 1:5.32-2ubuntu0.4                 |
| flex              | 2.6.4-6                           |
| ftp               | 0.17-34                           |
| gnupg2            | 2.2.4-1ubuntu1.5                  |
| haveged           | 1.9.1-6                           |
| imagemagick       | 8:6.9.7.4+dfsg-16ubuntu6.13       |
| iproute2          | 4.15.0-2ubuntu1.3                 |
| iputils-ping      | 3:20161105-1ubuntu3               |
| jq                | 1.5+dfsg-2                        |
| lib32z1           | 1:1.2.11.dfsg-0ubuntu2.1          |
| libc++-dev        | 6.0-2                             |
| libc++abi-dev     | 6.0-2                             |
| libcurl3          | 7.58.0-2ubuntu3.18                |
| libgbm-dev        | 20.0.8-0ubuntu1\~18.04.1          |
| libgconf-2-4      | 3.2.6-4ubuntu1                    |
| libgsl-dev        | 2.4+dfsg-6                        |
| libgtk-3-0        | 3.22.30-1ubuntu4                  |
| libmagic-dev      | 1:5.32-2ubuntu0.4                 |
| libmagickcore-dev | 8:6.9.7.4+dfsg-16ubuntu6.13       |
| libmagickwand-dev | 8:6.9.7.4+dfsg-16ubuntu6.13       |
| libsecret-1-dev   | 0.18.6-1                          |
| libsqlite3-dev    | 3.22.0-1ubuntu0.5                 |
| libtool           | 2.4.6-2                           |
| libunwind8        | 1.2.1-8                           |
| libxkbfile-dev    | 1:1.0.9-2                         |
| libxss1           | 1:1.2.2-1                         |
| locales           | 2.27-3ubuntu1.6                   |
| m4                | 1.4.18-1                          |
| mediainfo         | 17.12-1                           |
| mercurial         | 4.5.3-1ubuntu2.2                  |
| net-tools         | 1.60+git20161116.90da8a0-1ubuntu1 |
| netcat            | 1.10-41.1                         |
| openssh-client    | 1:7.6p1-4ubuntu0.7                |
| p7zip-full        | 16.02+dfsg-6                      |
| p7zip-rar         | 16.02-2                           |
| parallel          | 20161222-1                        |
| pass              | 1.7.1-3                           |
| patchelf          | 0.9-1                             |
| pkg-config        | 0.29.1-0ubuntu2                   |
| pollinate         | 4.33-0ubuntu1\~18.04.2            |
| python-setuptools | 39.0.1-2                          |
| rpm               | 4.14.1+dfsg1-2                    |
| rsync             | 3.1.2-2.1ubuntu1.4                |
| shellcheck        | 0.4.6-1                           |
| sphinxsearch      | 2.2.11-2                          |
| sqlite3           | 3.22.0-1ubuntu0.5                 |
| ssh               | 1:7.6p1-4ubuntu0.7                |
| sshpass           | 1.06-1                            |
| subversion        | 1.9.7-4ubuntu1.1                  |
| sudo              | 1.8.21p2-3ubuntu1.4               |
| swig              | 3.0.12-1                          |
| telnet            | 0.17-41                           |
| texinfo           | 6.5.0.dfsg.1-2                    |
| time              | 1.7-25.1build1                    |
| tk                | 8.6.0+9                           |
| tzdata            | 2022a-0ubuntu0.18.04              |
| unzip             | 6.0-21ubuntu1.1                   |
| upx               | 3.94-4                            |
| wget              | 1.19.4-1ubuntu2.2                 |
| xorriso           | 1.4.8-3                           |
| xvfb              | 2:1.19.6-1ubuntu4.10              |
| xz-utils          | 5.2.2-1.3ubuntu0.1                |
| zip               | 3.0-11build1                      |
| zsync             | 0.6.2-3ubuntu1                    |


