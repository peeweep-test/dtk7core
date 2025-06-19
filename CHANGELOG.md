# Changelog

All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## [5.7.16] - 2025-06-19

### Added

- Add debian
- Add install file
- Add DSettingsGroup
- Add dtk-settings-tool
- Add conflicts
- Add license
- Add DStandardPaths
- Add tests
- Add miss libgsettings-qt-dev
- Support gsettingsbackend, remove dsettings-key
- Add macro D_DECL_DEPRECATED
- Add dpinyin
- Add cmake package search configure
- Add DtkCore and dtkcore_config.h headers
- Add .qmake.conf file
- Add a mathmatic unit conver tools to format numbers.
- Add the "version.pri" file
- Support set default value
- Support qt module
- Support generate cmake with qt function
- Add group interface for DSettingsGroup
- Add get option interface
- Add hide support for group
- DDBusSender class is useful tools to make a dbus call
- Support new build package ver
- Support set file log path
- Support dtk_translations
- Add symbols
- Add LIBDTKCORESHARED_EXPORT for windows
- Add DSysInfo class
- Add depend "deepin-desktop-base"
- Add chinese documentation for dtimeunitformatter
- Add chinese documentation for DDiskSizeFormatter
- Add chinese documentation for DAbstractUnitFormatter
- Add docs for DStandardPaths
- Add doc for DSettings/DSettingsBackend
- Add GSettingsBackend/QSettingBackend
- Add DRecentManager class.
- Add documentation for DRecentManager.
- Add singleton
- Support connan build
- Add chinese docs fir DSettingsOption
- Add document for DObject
- Add the "buildQMAKEProject" test function for dtk_qmake
- Add DNotifySender
- Support gitlabl auto build
- Add library gsettings schema
- Add copy constructor
- Add class for exposing invokable to D-Bus.
- Support deepin distribution info config file
- Add DVtableHook
- Add DTrashManager
- Add DFileSerices
- Add ddeDisplayName() for DDE applications
- Support override global vtable of class
- Add class template argument for overrideVfptrFun
- Add personal edition support and check
- Support get installed memory size from lshw
- Add symbols file
- Add rpm spec
- Add class DThreadUtils
- Add rpm build required gtest-devel
- Add ut for dsysinfo
- Add qdbusxml2cpp-fix
- Add global function to get dtk Version
- Add data type check for config
- Add DStandardPaths::paths(DSG type) interface
- Add DStandardPaths::paths(DSG type) interface
- Add DSGApplication class
- Add LIBDTKCORESHARED_EXPORT for DSGApplication
- Add check for filesystemwatcher
- Add data type check for config
- Add Gentoo for DSysInfo (#63)
- Add NixOS for DSysInfo (#62)
- Add the permission management for files
- Add package for doc
- Add ddbusinterface
- Add Dexpected class
- Add Derror class
- Add docs for Derror and Dexpected class
- Add CMake rules for installing dexpected.h
- Add sysinfo interface
- Add default template parameter to type E
- Add DError as default template parameter to DUnexpected
- Add ddbusextendedabstractinterface
- Docs: add doxygen docs
- Docs: add doxygen theme
- Docs: add dcifile docs
- docs: add dconfig docs
- Add docs for util
- Add docs for settings
- Chore: add ISSUE_TEMPLATE
- Add docs for ddbussender.h
- Add docs for formatters
- Add docs for settings
- Add docs for settings
- Add docs for settings
- Add docs for settings
- Add docs for settings
- Add command tree and install dci tool
- Add docs for dconfigfile
- Add docs for ddesktopentry
- Add example for ddesktopentry
- docs: add example for dconfig
- Add example for dsysinfo
- Add linglong build support
- Add example for dconfigfile
- Add support for cmake target link
- Add some info about DExpected and DDBusInterface
- Add DtkDConfig package
- Add pie and as-needed linker flags for exe
- Add example for dsettings
- Docs: add doxygen theme
- Docs: add dtrashmanager.zh_CN.dox
- Add chinese2pinyin polyphonic support
- Feat: add journal appenders
- Support Qt6
- Chore(CI): add OBS workflows
- Support XDG_SESSION_DESKTOP set to DDE
- Add color to ConsoleAppender
- Add license infomation feature
- Support dtk6core build
- Add DThreadUtils class
- Add ut for DDbusSender
- Add systembus send support
- Add some unit test
- Support Qt 6.4 build
- Add DtkBuildHelper depends
- Add synchronization workflow
- Add flag UserPublic
- Add utils function
- Feat(dstandardpaths): add XDG_STATE_HOME
- Add dtk dbus generate function
- Support to set appId for DConfig
- Fix(qdbusxml2cpp): support qt 6.7
- Add nullptr check
- Feat: support Qt 6.8
- Support auto generate the Qt code from a dconfig's json
- Supports create generic config by dconfig2cpp
- Add copyright for dconfig_org_deepin_dtk_preference.hpp
- Add QPointer check for parent object safety
- Add missing UosMilitary edition type cases
- Feat(ci): add auto release
- Add license for VERSION.in

### Changed

- Merge dtkbase
- Merge dlog
- Merge filesystem
- Merge dsettings
- Merge util
- Change package name libdtkcore to libdtkcore1
- Conflicts libdtkcore
- Update so version to 2.0
- Move tool to lib/dtk2
- Fix cannot run test by make check
- Update license
- Create gsettingsbackend
- Release 2.0.5
- Update links in README
- Release 2.0.5.2
- Correct typos in src/log
- Release 2.0.5.3
- Release 2.0.6
- Give preference to using the git command to get the version when VERSION is empty
- Set verion when build
- Make version parser easier
- Install "version.pri" to libdtk/modules
- Update support Qt version to 5.6
- Split tool to libdtkcore-bin
- Config pkg config with dtk_module
- Release 2.0.7
- Set the default value of includes.path on dtk_build.prf
- Enable nonblocking mode in filesystem watcher
- Release 2.0.8
- Release 2.0.8.1
- Rebuild dtkcore
- Release 2.0.9
- Fallback to lsb-release if same property is empty on os-release
- Update version number for expermimental
- Documentation for DBaseFileWatcher
- DFileWatcher and DFileWatcherManager
- Release 2.0.9.5
- DPathBuf
- DSettingsOption/DSettingsGroup
- Release 2.0.9.8
- Release 2.0.9.9
- Release 2.0.9.10
- Update experminal package version
- Release 2.0.9.11
- Release 2.0.9.12
- Release 2.0.9.13
- Release 2.0.9.14
- Save dpkg-parsechangelog calls in debian/rules
- Update CHANGELOG.md
- Release 2.0.9.16
- Release 2.0.9.17
- Allow the same appender object to be registered to different categories
- Update CHANGELOG.md
- Correct a typo
- Update CHANGELOG.md
- Update symbols file
- Update CHANGELOG.md
- Correct a typo
- Update CHANGLE.md
- Use commit count for the package version
- Allow dtk-settings-tools skip json key translation
- Revert "remove version config"
- Update packages to version 5
- Revert "update packages to version 5"
- Export defines "DTK_LIB_DIR_NAME" "DXXX_TRANSLATIONS_PATH" "DXXX_TRANSLATIONS_DIR"
- Adjust responsibility of the prf files
- DtkTools module for libdtkcore-bin
- Merge branch 'cmake-for-settingtools' into 'master'
- Update the package version to 5.0.0
- Rebuild
- DSecureString which always fill 0 on delete
- Move the Chinese2Pinyin codes to dpinyin.cpp
- Release 5.0.3
- Basic support to parse xdg-desktop-entry files
- New interface for getting information of different organization
- Update .gitlab-ci.yml
- Release 5.1.2
- Switch to LGPLv3 license
- Disable dh_makeshlibs
- 集成dabi的json文件到包中
- Os-version 系统识别方案新接口
- Improve english in dtk_translation.prf
- Fix shebang
- DThreadUtils添加一些函数重载
- Initial packit setup
- 添加GTest测试单元
- 打包可以触发单元测试
- 重载dh_makeshlibs
- DVtableHook support std::function
- DVtableHook support const member function
- 增加单元测试覆盖率
- 添加教育版专用设备版本识别
- 单元测试的类名修改
- 调整单元测试结构
- Test.pro 微调
- 适配多版本合并（移除冲突添加依赖）
- 修改ignore文件和删除无用prf文件
- 屏蔽私有类符号
- 导出DObjectPrivate符号
- Improve log file name
- 更新DVtableHook的注释
- Update abi json file
- 适配家庭版社区版新版本号，调整读取逻辑
- Dtkcore支持一包多依赖
- 输出测试报告xml文件
- 添加漏掉的日志类型
- Asan无日志生成则添加空文件
- 更新qdoc注释信息
- 移除单元测试sleep
- 添加单元测试
- 添加log模块单元测试
- 添加单元测试
- 添加filewatcher,util,gsettings单元测试。
- 打印memoryTotalSize接口的输出结果
- 添加异步任务功能类 DAsync
- 清除 QDoc 运行时的警告信息
- Update DTK_VERSION
- 添加 DStandardPaths
- 新增 DConfigFile 类
- Add DConfig class
- 重构DConf Class并适配DBus service开发。
- 重构DConFile Class并适配DBus service开发。
- Merge branch 'dev/config'
- 增加qmake/cmake文件生成条件
- DtkVersionString return empty string
- 添加配置策略文件安装时非uos的deb打包规范的支持.
- 修复 euler 编译失败
- 规范DConfigFile命名及部分暴露接口
- 取消dasync的部分单元测试
- Warning only in debug mode
- Not check dtkcore2 and dtkcore5
- DSettings适配兼容DConfig
- Osversion中OEM标识兼容
- 主动拉起未启动的 dconfig 服务
- 修改单元测试生成目录
- Add interface for Dconfig
- File Sync from linuxdeepin/.github (#48)
- Update README.md
- Sync by https://github.com/linuxdeepin/.github/commit/41155231b0dece553ad9b426ea5b891a423a0e40 (#57)
- File Sync from linuxdeepin/.github (#58)
- Sync by https://github.com/linuxdeepin/.github/commit/99dfe0471c3124c80af8fed2611b8489c34d5a17 (#65)
- Dtkcore_config.h miss include some Class
- Os-version中增加对abc字段的适配
- Feat: update archlinux build
- Chore: build doxygen documentation
- 加载dconfigfile时，添加value字段的检测
- 支持 DCI 文件的解析
- 添加  DDciFileEngine
- 新增 DDciFile::copy 接口
- 为 DCI 文件添加软链接支持
- DDciFileEngine 支持判断内部路径是否为根目录
- 添加注册 DDciFileEngine 的接口
- 支持 DCI 文件保持按数字排序
- Add the dci command tool project
- 允许获取 dci 内部软链接文件的原始数据
- Merge branch 'dev/dci' into v23
- Change the way to get appId
- Not check dtkcore2 and dtkcore5
- DSettings适配兼容DConfig
- Osversion中OEM标识兼容
- 主动拉起未启动的 dconfig 服务
- 修改单元测试生成目录
- Add interface for Dconfig
- Unit error in loongarch64
- Unit error in loongarch64
- 更新changelog
- 加载dconfigfile时，添加value字段的检测
- Update changelog
- Update changelog
- Merge branch 'develop/snipe'
- Merge pull request #72 from kegechen/master
- Sync by (#73)
- Sync by (#76)
- Sync by https://github.com/linuxdeepin/.github/commit/fed570b6d7fe6ca5b435e6d4c8ef4985299cabf7 (#77)
- Adapt REUSE license header
- Sync by https://github.com/linuxdeepin/.github/commit/8cd7951872aad11af6f6f0013b35969154cb7920 (#84)
- Sync by https://github.com/linuxdeepin/.github/commit/1086c873ff7f018a066f2d39d5ac893eb5351057 (#85)
- Sync by (#86)
- Sync by https://github.com/linuxdeepin/.github/commit/ab82576125f34a03d243a0a992614b5ee23292f2 (#87)
- Tocmake
- Sync by https://github.com/linuxdeepin/.github/commit/8fb17418f4be773a64341f0e7d54f0b3dd02c38a (#89)
- Add win32 files and delete pri files
- Update REUSE license header
- Add zh_CN readme
- Unit test, coverage
- Sync by "
- Modify some nonstandard writing
- Use DSG_PREFIX_PATH set PREFIX
- Define mkspecs self
- Use CMakePackageConfigHelpers to generate better config.cmake
- Use SameMajorVersion in version file
- 微调 ddbusinterface 类
- Chore: update changelog
- Set DtkCore_LIBRARY_DIRS
- Optimize compilation parameters
- Sync by https://github.com/linuxdeepin/.github/commit/6fbf8e00b96efe3fd50deef879f6679b80fa59a8
- Change Dexpected to DExpected
- Update Log license
- Update README
- Correct function name has_value to hasValue
- Update changelog
- Sync by https://github.com/linuxdeepin/.github/commit/d15debb9d3b7fbf5feb0f00a1bb92912f5bc386c
- Sync by https://github.com/linuxdeepin/.github/commit/50ad27fb2a32385ef0683164fded219b74ea11f0
- Docs: update doxygen docs
- Update changelog
- Sync by https://github.com/linuxdeepin/.github/commit/6aa579e31cc66ec92da0523a11b7f638f668833b
- Chore: update references doc
- Docs: update docs
- Docs: update docs dlog modules
- 完善cpu信息获取接口（cpuModelName）
- Docs: Standardize documents, add groups
- Docs: update Logger documents
- Docs: update dlog documents
- Sync by https://github.com/linuxdeepin/.github/commit/3de30af6dca0eb1716283dc47998b5a455d7a614
- Docs: update filesystem documents
- Update docs for util
- Update dcapfile document
- Move namespace
- Format code
- Docs: update README.md
- Update documents
- Update docs
- Update MainPage
- Update docs
- Link to real source file when export
- Label DAsync as deprecated
- Chore: Update dsysinfo.cpp
- Update changelog
- Revert "chore: Update dsysinfo.cpp"
- Use mountpoint to find root device
- Add DTextEncoding class.
- Chore: Modify the wrong mark in dsysinfo.h
- Feat: optimization logic for other distribution
- Modify include directories policy
- Modify PKGBUILD command
- Sync by https://github.com/linuxdeepin/.github/commit/d45f73b2d05d5dcbb29185b492c8325597549171
- Change include and tool directory
- Update changelog
- Docs: update docs
- Update dfilesystemwatcher docs
- Feat: update file watcher manager
- Docs: update dfilewatchermanager.zh_CN.dox
- Correct unsuitable description
- Chore: update changelog
- Docs: update log index doc
- Update readme
- Chore: update PKGBUILD
- Docs: update docs
- Private link QtCorePrivate
- Log file function and line by default
- Add generic configuration support for DConfig (#236)
- Update changlog
- Specify dtkcommon-dev version
- Update changelog
- Removing the same code for homePath
- Append to all appenders when category is not registered
- Support cache to be relocated for DConfigFile
- Update to 5.6.9
- Sync by https://github.com/linuxdeepin/.github/commit/c5d10d3aeb9233a70f6290cb89d3b193f7b1f804
- Sync by https://github.com/linuxdeepin/.github/commit/2dd22560f77d8b9b943ee8ae0f039ad8e36a4d27
- Update to 5.6.10
- Rename config function
- Chore: Update dconfig's example
- Bump version to 5.6.11
- Sync by https://github.com/linuxdeepin/.github/commit/2e5e092ba3f86b16d1aabbabcf0bfd2ae65b19c8
- Back cache of caculate memoryInstalled
- Revert deleted function for DVtableHook
- Bump version to 5.6.12
- DConfig add check for no existed item when override
- DConfig add check for subpath
- DConfig exports metadir's implementation
- Update changelog
- Chore: function need to be marked as override
- Ignore doxygen-theme folder
- Change OUTPUT_DIR variable in cmake
- Deprecate some interfaces in dtk6
- Reduce compilation warnings
- Chore(dcapmanager): RuntimeTime -> RuntimeDir
- Sync by https://github.com/linuxdeepin/.github/commit/559e91167d4919644f37bbcf123eb0651c1528ea
- Make test-recoverage.sh runable again
- Should include QVector headers
- Dsysinfo tweak
- Update changelog
- Dlog example tweak
- Use spdlog reimplement dlog
- Update changelog
- Ut linked dtkcore instead of source code
- Tweak CMakeLists
- Qch docs tweak
- Console with color at tty
- Update changelog
- Update changelog
- Add isDefaultValue for DConfig
- Show help if argc < 2
- Chore: correct typos in DtkSettingsToolsMacros.cmake
- Dpinyin tweak
- Update changelog
- Update changelog
- Implement DSGApplication::getId
- Keep order when deduplication
- Update changelog
- Allow skip including headers of annotations
- Update changelog
- Update changelog
- Update changelog
- Update changelog
- Update changelog
- Update changelog
- Update changelog
- 允许基于dtk开发的应用动态控制其日志输出等级
- 增加registerLoggingRulesWatcher接口
- DeepinType类型增加军用版
- Loggingrules config move to preference
- Fallback to dsgconfig value
- Update changelog
- Use '&&' and '||' instead of 'and' and 'or'
- Update changelog
- Log files move to dtklog
- Update changelog
- Update changelog
- Feat: 增加智能终端设备类型 (#434)
- Update changelog
- Update changelog
- Update changelog
- Update changelog
- Update changelog
- Update changelog
- Update changelog
- Update changelog
- Update changelog
- Bump version to 5.7.10
- Async get dconfig value for DLog
- Export ProductType for QML
- Dconfig2cpp generated codes supports qml
- Bump version to 5.7.11
- Add files generated by qdbusXML2cpp and DCONG2cpp
- Dconfig2cpp always add bindableFoo functions on Qt6
- Bump version to 5.7.12
- Bump version to 5.7.13
- Bump version to 5.7.14
- Update REUSE license file patterns
- Bump version to 5.7.15
- Bump version to 5.7.16
- Support VERSION file
- Update .syncexclude
- Rename dtkcore.spec to dtk7core.spec
- Update auto-release.yml
- Update auto-release.yml

### Fixed

- Not select python version
- Build failed on used dbasefilewatcher.h project
- Windows build failed
- Make macosx build success
- Break forever loop for syncing backend data
- Fix support for kfreebsd and hurd
- Adapt lintian
- Set its value only if VERSION is empty
- Set default build version for debian changelog
- Awk script failed
- Fix a bug cause packaging on hurd failed
- Develop package no install the "version.pri" file
- Fix dtk-settings install path
- Set default should not use
- Read settings value failed
- Better static lib support
- Cmake link depends
- Set the VERSION from dtkcore version on other dtk project
- The value of \"includes.path\" is wrong
- Not include DDBusSender
- Build failed on windows
- Premissions of dtk_translation.prf
- Fix a typo
- Update email format
- Update symbols
- Non array type value is wrong on parse josn file
- Fix a typo
- Fix a typo
- Can not build on Qt 5.6.1
- Fix a typo
- Can't get correct disk size in some case
- Url encoded.
- Chinese doc
- Uniform url format.
- Xbel file does not exist.
- Compatibility with Qt 5.6
- Url encoding
- Include unistd.h instead of sys/unistd.h
- Missing default constructor
- Fix some typos
- Use main project c/cxx/ld flags on build deepin-os-release
- Failed build the deepin-os-release on Qt 5.7.1
- Deepin-os-release support cpu model and other info query
- Fix a typo
- Crash at application
- Https://github.com/linuxdeepin/dtkcore/issues/10
- Cross-builds incorrectly, built packages contain paths from build architecture
- Crash when calling getOption() if option doesn't exist
- Use "$$ROOT_DIR" replace "$$mod_inst_pfx/.."
- Dtk-settings binary location for libdtkcore-bin package
- The pkg-config "Requires" values
- The PKG_MODULE_DEPENDS dno't add Qt modules
- Use DTK_MODULE_NAME replace TARGET
- Fix pkgconfig file format
- Make sure the action exists before invoking it.
- DFileSystemWatcher only emits signal for one path if it's bound to multiple locations.
- File moved detection.
- Removing path from DFileSystemWatcher has unpredictable results.
- Batch_pathmap should be a QMultiHash.
- Should ensure deepin info
- Ensure uos is equivalent to deepin
- Fix warnings of code(DSysInfo)
- Saving wps office sheet modify event duplicated
- Build failed on MacOS
- Parse error with some desktop files
- Stderr warning from deepin-os-release tool
- Task17545【KLU-KK】【ARM】【build14】【DDE】【控制中心--系统信息】系统信息首页关于机器处理器的品牌类型信息显示不全
- Fix tow tag on same commit
- Bug-20975 DSettings::reset emit too many valueChanged
- 加入symbols文件后有的架构打包失败
- Dpkg-source build error
- 适配os-release中ID的修改
- 64k forceWriteMemory crashed
- Correct tools output message typo
- 修复安全扫描分析处理报告中Error的问题
- Dsettings存在内存泄露问题
- 解析desktop文件中多国语言不支持短名
- Dtk_module文件修改
- Dtk_cmake文件修改
- 更新api-json文件
- Vtablehook failed
- 同步修复可能存在hook失败的问题
- Build lintian error on mips
- 默认日志路径目录总是会创建的问题
- 修复没有deepin-version文件的环境下访问空指针的问题
- Gerrit build error
- Dtkcore build dependcy
- Dtkcore的依赖问题
- 适配多版本共存,移动dtkcommon项目中的3个cmake文件到dtkcore
- 修复setlogFilePath()函数问题
- Logfile path bugs
- Qdbusxml2cpp-fix not installed
- Gerrit build error
- Tests project qmake error
- Eliminate warning
- Rpm schemas not installed
- Add memory leak detection parameters
- Unit test memory leak check failed due to AddressSanitizer.
- Global function is missing
- Unit test memory leak.
- Renaming a nonexistent file will report an error
- 处理单元测试脚本的返回值
- 删除Log中不必要的空白字符
- 修复thread单元测试未定义行为
- 单元测试运行失败
- 主机名只能获取一次
- 获取用户名时间过长
- Ut failed on loogarch
- 修改警告处代码，去除warning警告
- DConfigFile内存泄露
- 单元测试报错
- 配置策略global配置项的cache保存路径错误
- Ut link error in dtk.
- Change directory of cache for dconfig
- 修复dtk单例模板缺陷
- Can not find QGSettings
- Fix doc generate error
- Unit error
- Can't access QStringList type data for DConfig
- Modify loading order of application meta path
- Dconfig can't support embed complex data type
- DSetting unit error and crash randomly
- Application crash when dconfig is invalid
- DConfig can't find resource
- Ut link error in community.
- 修复开启 -Werror=format-security 时编译错误
- Soft link error
- Modify loading order of application meta path
- Ut links failed
- Ut link error in dtk.
- Change directory of cache for dconfig
- 修复dtk单例模板缺陷
- Can not find QGSettings
- Fix doc generate error
- Unit error
- Can't access QStringList type data for DConfig
- Modify loading order of application meta path
- Dconfig can't support embed complex data type
- DSetting unit error and crash randomly
- Application crash when dconfig is invalid
- DConfig can't find resource
- Fix build warning
- DConfig'appId assertion failed
- AppId gets error
- Optimize the use of DCI tools
- Fix: fallback to the user directory if no a valid global config directory
- Fix: link to dl
- Invalid digit "8" in octal constant
- Fix a typo in dfilewatcher.cpp
- Fix: missing include folder while generating documentation
- README link
- DConfig can't load meta file
- Fix: wrong option() usage in CMakeLists.txt
- Build failed using clang
- Wrong target
- Use FULL install path
- Don't check DtkCore_TOOL_DIR cause split pkgs
- Fix(DDBusInterface): can not emit property changed signal
- DDbusInterface Can't route complex dbus type
- Missingdefinition
- Fix reinit imcomplete instantiation
- Fix likely/unlikely type convertion error
- Fix logic error of DExpected<void> partial specialization's destractor
- Fix missing std::move for rvalue reference qualified function value
- Missing sw_64 architecture
- Docs: fix some error in doxygen docs.
- Logger constructor crash
- Fix license
- Missing implementation and obsolete Member
- Fix: fix ddcifile docs
- Fix: fix ddcifile docs
- Remove ASan check for debug
- Fix: fix dconfig docs
- Fix: fix README.md
- Fix linking error
- Fix: qch does not generate the problem
- Fix: qdbusxml2cpp-fix error
- Fix trivially copy/move constructiable type can't be constructed
- Dtkcore namespace not using
- Fix lintian warnings
- Fix DVtableHook and DConfig's unit testing
- Cleaning path about dconfigfile
- Losing dconfig info when compiling and packaging
- Fix: Removing strong dependencies on systemd
- Lossing quotation mark for DSG_DATA_DIR macro (#259)
- Missing BUILD_WITH_SYSTEMD macro (#258)
- Qch generate error
- Compiling error in qt5 (#270)
- Fix compile error when using qt6
- Temporarily fix the dead loop generated by QDebug destructor when compiling with the relocatable feature of qt
- Fix bug of unit test under clang
- Fix MainPage typo
- Fix incomplete copy of Vtable
- Adjust dependencies in PKGBUILD
- AppId fetch error when fallback to applicationName
- No log file
- Sync with qt5platform-plugins
- Incorrect DSecureString destructor
- Must set CMAKE_INSTALL_PREFIX before GNUInstallDirs
- Color is in file if is redirect
- Wrong use of option and wrong macro
- Calling delay in DDBusSender
- Fix cannot get the right type
- DConfig's `subpathIsValid` produces error
- Failed ut
- Build faild on Qt6
- Fix build failed due to gcc compiler bug
- Ut_dfilewater failed on Qt6
- DTextEncoding ut failed in Qt6.
- Fix DTextEncoding warnings.
- Fix: move Qt CorePrivate to target private link
- Qdbusxml2cpp-fix not in path
- Fix: updateProp cannot convert to property type
- Fix: typo in xdg
- InternalPropSet nerver emit propertyChanged
- FileAppender log level not set
- Missing dependency qttools5-dev
- Incorrect version passed to cmake in build
- Can't clear cache when reset for DConfig in FileBackend
- Compiling failed in lower libspdlog-dev
- Missing parameter passing for synchronization
- Skip failed unit test
- Compiling failed in libspdlog-dev before 1.4.0
- Cmake failure when env is null
- Type error for qdbusxml2cpp
- Fix: correct Dtk6SettingsToolsMacros.cmake path
- Log files limit not work
- App blocked when AM is unavailable
- Fix relative path invalid link
- Fix docs typo
- DConfig add check for name
- Lossing value when save DConfig
- Fix undefined reference errors on spdlog 1.14.0
- DConfig add check for AppId
- DConfigFile is invalid when AppId is empty
- Lshw查询内存大小时返回多元素数组,修正解析过程
- 从文件中读取deepinType和productType值时因为权限问题会失败
- 修复计算 build 版本号错误的问题
- 修复日志格式时间戳显示异常问题
- Crashed when access DSGApplication::id early
- Build faild on Qt 6.7.1
- DDBusInterface signal loss
- Error appid from `getAppIdFromAbsolutePath`
- JournalAppender not work
- Debian/rule use tab instead of space
- HasVtable is incorrect when destructing
- Compilation on Qt 6.8.1
- Pidfd leak
- Double value is converted to int for DConfig
- Build failed on Qt6
- Resolve compilation failure on Qt 6.9
- Correct bitwise operation in dconfig status tracking
- .deepin@main -> .deepin@master

### Removed

- Remove unused gsettings-qt from filesystem.pri
- Remove unless config
- Remove conflicts
- Remove conflicts
- Remove build version from install path
- Remove some symbols check to support qt 5.10.1
- Remove qt symbols
- Remove deepin-desktop-base buildep
- Remove check failed symbols
- Remove version config
- Remove deepin-desktop-base dept
- Remove assert in ensureOsVersion
- Remove assert in ensureOsVersion
- Fix: remove not supported syntax for README (#75)
- Remove deprecated script
- Remove unnecessary variant member
- Delete an undefined overloaded function
- Remove dependency search
- Remove doubleLoadCheck
- Delete useless doxygen theme
- Remove useless debian/missing-sources
- Docs: remove DConfig.doc
- Remove DCapFSFileEngine
- Chore: remove build warning
- Remove ddbusinterface property cache
- Remove libdtkcommon depends
- Remove unused pro files
- Remove decltype(auto) for dutil
- Remove unused code
- Remove warning for dbusxml2cpp in qt6
- Remove LoggingRules interface
- Remove unnecessary link libraries

<a name="5.7.14"></a>
## 5.7.14 (2025-04-12)

### Bug Fixes

* resolve compilation failure on Qt 6.9

<a name="2.0.14"></a>
## 2.0.14 (2019-05-23)

#### Bug Fixes

* **DSettings:**  crash when calling getOption() if option doesn't exist ([90ac734b](https://github.com/linuxdeepin/dtkcore/commit/90ac734b872203ea698808a7197aa7a9c7e2b5bd))



<a name="2.0.12"></a>
## 2.0.12 (2019-04-18)




<a name="2.0.11"></a>
## 2.0.11 (2019-04-17)


#### Bug Fixes

*   Cross-builds incorrectly, built packages contain paths from build architecture ([8d32577a](https://github.com/linuxdeepin/dtkcore/commit/8d32577a89e54b5c9c834caae83d98e50f59df77))
*   https://github.com/linuxdeepin/dtkcore/issues/10 ([3f99873a](https://github.com/linuxdeepin/dtkcore/commit/3f99873a786f6830688ecd0d8d2e2bf8dfb63ce0))



<a name="2.0.10"></a>
## 2.0.10 (2019-03-27)


#### Bug Fixes

*   crash at application ([d852a218](https://github.com/linuxdeepin/dtkcore/commit/d852a21811f9f86e04274fc9f732d7c7a210ef3f))

#### Features

*   add DNotifySender ([89bbcd7c](https://github.com/linuxdeepin/dtkcore/commit/89bbcd7c3821985bb2bca51247394fd4a65b25bf))



<a name="2.0.9.17"></a>
## 2.0.9.17 (2019-02-26)




<a name="2.0.9.16"></a>
## 2.0.9.16 (2019-02-26)


#### Bug Fixes

*   deepin-os-release support cpu model and other info query ([cbeb47c9](https://github.com/linuxdeepin/dtkcore/commit/cbeb47c97e31d2b5dd3c198c60ee74332fecb293))



<a name="2.0.9.15"></a>
## 2.0.9.15 (2019-01-25)


#### Bug Fixes

*   failed build the deepin-os-release on Qt 5.7.1 ([8bae8654](https://github.com/linuxdeepin/dtkcore/commit/8bae8654bdb20a7f773130d22b9db139460ba575))
*   use main project c/cxx/ld flags on build deepin-os-release ([86dbd507](https://github.com/linuxdeepin/dtkcore/commit/86dbd507c1b3b101c1816f091782430ec1ce20ce))



<a name="2.0.9.14"></a>
## 2.0.9.14 (2019-01-02)




<a name="2.0.9.13"></a>
## 2.0.9.13 (2018-12-28)




<a name="2.0.9.12"></a>
## 2.0.9.12 (2018-12-24)


#### Bug Fixes

* **DPathBuf:**  missing default constructor ([74374cb4](https://github.com/linuxdeepin/dtkcore/commit/74374cb4cf0245ab1fe73f62fe0d13566f945db3))

#### Features

*   support connan build ([ba2d213f](https://github.com/linuxdeepin/dtkcore/commit/ba2d213fd6c7e36e118288305e5892c339250623))



<a name="2.0.9.11"></a>
## 2.0.9.11 (2018-12-14)




<a name="2.0.9.10"></a>
## 2.0.9.10 (2018-12-05)


#### Bug Fixes

*   include unistd.h instead of sys/unistd.h ([39c50a13](https://github.com/linuxdeepin/dtkcore/commit/39c50a1398c34123e3806a3060a4c64e7f45ed68))
*   url encoding ([4a6b7b61](https://github.com/linuxdeepin/dtkcore/commit/4a6b7b61bb3ad9ab417eda69249b5e9aced0aa97))



<a name="2.0.9.9"></a>
## 2.0.9.9 (2018-11-19)


#### Features

*   add DRecentManager class. ([a2defafd](https://github.com/linuxdeepin/dtkcore/commit/a2defafdcf57078461221c665e322287a43d24a8))

#### Bug Fixes

*   compatibility with Qt 5.6 ([0ec7f3ce](https://github.com/linuxdeepin/dtkcore/commit/0ec7f3ce389b323ecb2b103801c1cd1d55f100fa))
* **drecentmanager:**
  *  xbel file does not exist. ([c57ffe71](https://github.com/linuxdeepin/dtkcore/commit/c57ffe714f26b1a8a8859e2ffbeeed3d75ee11a1))
  *  uniform url format. ([413a8988](https://github.com/linuxdeepin/dtkcore/commit/413a8988116708ab8bcf9efbb9bc8f52e048efa5))
  *  url encoded. ([e234a8cc](https://github.com/linuxdeepin/dtkcore/commit/e234a8cc5ad9d2c14a16950838115c4f2f27c605))
* **recent:**  chinese doc ([fb256461](https://github.com/linuxdeepin/dtkcore/commit/fb256461d1bdb0862b1a3a129978fc3932a6bcab))



<a name="2.0.9.8"></a>
## 2.0.9.8 (2018-11-09)


#### Bug Fixes

*   can't get correct disk size in some case ([20a12b62](https://github.com/linuxdeepin/dtkcore/commit/20a12b622ea7b01f0616c15a8af85e31fc2d36cb))



<a name="2.0.9.5"></a>
## 2.0.9.5 (2018-10-26)


#### Features

*   update version number for expermimental ([02b5d5c1](https://github.com/linuxdeepin/dtkcore/commit/02b5d5c1e01a05f57651b774b02cae31ef9a549f))



<a name="2.0.9"></a>
## 2.0.9 (2018-07-20)


#### Bug Fixes

*   remove qt symbols ([57ec78ba](https://github.com/linuxdeepin/dtkcore/commit/57ec78ba685a53692b0260d3d558d8b0915fc3e4))
*   non array type value is wrong on parse josn file ([9f138664](https://github.com/linuxdeepin/dtkcore/commit/9f13866439d8d650893434594da023e7d331d866))



<a name="2.0.8.1"></a>
### 2.0.8.1 (2018-05-14)


#### Bug Fixes

*   update symbols ([f6c53cc4](https://github.com/linuxdeepin/dtkcore/commit/f6c53cc493c1bcf55dca54dbf500e2e484af73c9))
*   add LIBDTKCORESHARED_EXPORT for windows ([6fb1096f](https://github.com/linuxdeepin/dtkcore/commit/6fb1096f6d0784937cf84f0e4ae1f5f7587085e5))
* **changelog:**  update email format ([cb09a0ca](https://github.com/linuxdeepin/dtkcore/commit/cb09a0cadcf2fa0ba271b1d98d3b96a993eb892b))



<a name="2.0.8"></a>
## 2.0.8 (2018-05-02)


#### Features

*   add symbols ([048de455](https://github.com/linuxdeepin/dtkcore/commit/048de4551bdd770aca5e9c12798362f913061654))



<a name="2.0.7"></a>
## 2.0.7 (2018-03-01)


#### Bug Fixes

*   cmake link depends ([cdfcff9e](https://github.com/linuxdeepin/dtkcore/commit/cdfcff9e2f3e92bc6dbb45644d2714d6c4dbdda0))
*   better static lib support ([99886406](https://github.com/linuxdeepin/dtkcore/commit/99886406a0cae849fad23286fdf64bb399e37da0))
*   read settings value failed ([cf1c7698](https://github.com/linuxdeepin/dtkcore/commit/cf1c769893773794dff5a67c235c5d1f3234541a))
*   set default should not use ([146529f6](https://github.com/linuxdeepin/dtkcore/commit/146529f6887e798606f2bf763ab8a760969bff26))
*   fix dtk-settings install path ([1893cff3](https://github.com/linuxdeepin/dtkcore/commit/1893cff301dacb546a246a4f824dab68eac51351))
*   develop package no install the "version.pri" file ([5667b562](https://github.com/linuxdeepin/dtkcore/commit/5667b562630565fca5abed690f3d3478dd3c7603))
*   awk script failed ([524a3fa6](https://github.com/linuxdeepin/dtkcore/commit/524a3fa6021ee54db416503520aea65ef0e2c3a0))
*   set default build version for debian changelog ([ec6e2a83](https://github.com/linuxdeepin/dtkcore/commit/ec6e2a8376c7aca7162b4fbb782b998c9a6ab630))
*   set its value only if VERSION is empty ([1836000c](https://github.com/linuxdeepin/dtkcore/commit/1836000c49eb149a6495322c4cbb1474d5d48204))

#### Features

*   add hide support for group ([e7e4fb66](https://github.com/linuxdeepin/dtkcore/commit/e7e4fb669276fbce61c6378e74ae82573e7c0313))
*   add get option interface ([d8682485](https://github.com/linuxdeepin/dtkcore/commit/d8682485a6737da83fb28f22335f1da1afb8956c))
*   add group interface for DSettingsGroup ([c876180f](https://github.com/linuxdeepin/dtkcore/commit/c876180f535e3027dce63628f31379ef874367ed))
*   support generate cmake with qt function ([524b0559](https://github.com/linuxdeepin/dtkcore/commit/524b055929b7be84375a45f9d10cbc3a0ecac6de))
*   config pkg config with dtk_module ([137b9138](https://github.com/linuxdeepin/dtkcore/commit/137b91388d9b9db24c8136dd4e2c6e690a5712c5))
*   support qt module ([17ca0de9](https://github.com/linuxdeepin/dtkcore/commit/17ca0de9156a320cea32208dcff2f8cdf7d6a237))
*   add the "version.pri" file ([07aab9fd](https://github.com/linuxdeepin/dtkcore/commit/07aab9fd6478c83c7bae1062f64b4bd20b21869c))
*   remove build version from install path ([3bf0bfb5](https://github.com/linuxdeepin/dtkcore/commit/3bf0bfb5f49c3e83d4c36cc33f219150bf3731d8))
*   make version parser easier ([6d3b4ead](https://github.com/linuxdeepin/dtkcore/commit/6d3b4ead7080158d1d8977bf7cf99ae842e574ec))
*   set verion when build ([9083dbd3](https://github.com/linuxdeepin/dtkcore/commit/9083dbd3e29bf9d06b1032901ba13848fa964f4c))
*   add .qmake.conf file ([2890f643](https://github.com/linuxdeepin/dtkcore/commit/2890f643a57c3532ab623410f7c6c6dbfdd6788d))
*   add DtkCore and dtkcore_config.h headers ([308a0cc4](https://github.com/linuxdeepin/dtkcore/commit/308a0cc41101499c04308b4ef3bb2fff4ab8d783))
* **DSettings:**  support set default value ([5fe9bfd0](https://github.com/linuxdeepin/dtkcore/commit/5fe9bfd0a5e20cef7393639712302825b803db29))



<a name="2.0.6"></a>
## 2.0.6 (2018-01-15)




<a name="2.0.5.3"></a>
## 2.0.5.3 (2017-12-27)


#### Bug Fixes

*   Adapt lintian ([27df15df](https://github.com/linuxdeepin/dtkcore/commit/27df15df32788002491a24f06f098a5f849a4988))
*   break forever loop for syncing backend data ([f70e500e](https://github.com/linuxdeepin/dtkcore/commit/f70e500ec2fd5c751e40833bdc4df586614bcff2))

#### Features

* **util:**  add dpinyin ([128d7d67](https://github.com/linuxdeepin/dtkcore/commit/128d7d678e921bc580dd732b14a454973397899c))



<a name="2.0.5.2"></a>
## 2.0.5.2 (2017-11-28)


#### Bug Fixes

*   make macosx build success ([af04bbe1](https://github.com/linuxdeepin/dtkcore/commit/af04bbe193a4b4251908f830d927ebdc8f4459e7))
*   windows build failed ([66c4c812](https://github.com/linuxdeepin/dtkcore/commit/66c4c812eb29634710642f4e9d6b3d69cc692cb2))

#### Features

*   add macro D_DECL_DEPRECATED ([89e49868](https://github.com/linuxdeepin/dtkcore/commit/89e49868f113ef01c03bcf5b6846eec95c428382))



<a name="2.0.5"></a>
## 2.0.5 (2017-11-06)


#### Bug Fixes

*   build failed on used dbasefilewatcher.h project ([34fbe4b3](34fbe4b3))
*   add miss libgsettings-qt-dev ([f61c1b54](f61c1b54))
*   not select python version ([7e7e8832](7e7e8832))

#### Features

*   support gsettingsbackend, remove dsettings-key ([26a29800](26a29800))
*   create gsettingsbackend ([b94b97b1](b94b97b1))
