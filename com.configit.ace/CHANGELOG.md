# Changelog
All notable changes to this package will be documented in this file.

The format is based on [Keep a Changelog](http://keepachangelog.com/en/1.0.0/)
and this project adheres to [Semantic Versioning](http://semver.org/spec/v2.0.0.html).

## [1.0.4]
### Changed
- Updated the following libraries to the latest version:
  - Configit.Ace.Configurator.Client.dll
  - Configit.Ace.Platform.Client.dll
  - Configit.Ace.Platform.Common.dll
- Removed the following dlls
  - Configit.ResourceRepository.Common.dll
  - Configit.ResourceRepository.Provider.dll
  - Configit.ResourceRepository.Publisher.dll
  - Configit.ResourceRepository.Storage.Manager.dll
  - Configit.ResourceRepository.Storage.Memory.dll
  - Configit.ResourceRepository.Storage.dll
- Added the following dlls
  - Configit.Internal.ResourceRepository.Common.dll
  - Configit.Internal.ResourceRepository.Provider.dll
  - Configit.Internal.ResourceRepository.Publisher.dll
  - Configit.Internal.ResourceRepository.Storage.Manager.dll
  - Configit.Internal.ResourceRepository.Storage.Memory.dll
  - Configit.Internal.ResourceRepository.Storage.dll
- Renamed the following .meta files
  - Configit.Internal.ResourceRepository.Common.dll.meta -> Configit.Internal.ResourceRepository.Common.dll.meta
  - Configit.ResourceRepository.Provider.dll.meta -> Configit.Internal.ResourceRepository.Provider.dll.meta
  - Configit.ResourceRepository.Publisher.dll.meta -> Configit.Internal.ResourceRepository.Publisher.dll.meta
  - Configit.ResourceRepository.Storage.Manager.dll.meta -> Configit.Internal.ResourceRepository.Storage.Manager.dll.meta
  - Configit.ResourceRepository.Storage.Memory.dll.meta -> Configit.Internal.ResourceRepository.Storage.Memory.dll.meta
  - Configit.ResourceRepository.Storage.dll.meta -> Configit.Internal.ResourceRepository.Storage.dll.meta

## [1.0.3]

### Fixed
- Modified the following meta files to prevent dlls from being included twice:
  - K4os.Compression.LZ4.dll.meta
  - System.Runtime.CompilerServices.Unsafe.dll.meta

## [1.0.2]

### Added
- The following libraries and associated meta files because they are dependencies:
  - K4os.Compression.LZ4.dll
  - System.Buffers.dll
  - System.ComponentModel.Annotations.dll
  - System.Memory.dll
  - System.Numerics.Vectors.dll
  - System.Runtime.CompilerServices.Unsafe.dll
  - System.Threading.Thread.dll
  - System.ValueTuple.dll

### Changed
- Updated the following libraries to the latest version:
  - BCrypt.Net-Next.dll
  - Configit.Ace.Configurator.Client.dll
  - Configit.Ace.Platform.Client.dll
  - Configit.Ace.Platform.Common.dll
  - Configit.Caches.LruCache.dll
  - Configit.ResourceRepository.Common.dll
  - Configit.ResourceRepository.Provider.dll
  - Configit.ResourceRepository.Publisher.dll
  - Configit.ResourceRepository.Storage.Manager.dll
  - Configit.ResourceRepository.Storage.Memory.dll
  - Configit.ResourceRepository.Storage.dll

## Fixed
- System.ValueTuple.dll is not active for any Unity target platform by default because it will most probably be added through another package already.

## [1.0.1] - 2022-03-28

### Added
- The following libraries and associated meta files which are need for a standalone build:  
  - BCrypt.Net-Next.dll
  - Configit.Caches.LruCache.dll
  - Configit.ResourceRepository.Storage.Manager.dll
  - Configit.ResourceRepository.Storage.Memory.dll
  - Microsoft.Extensions.Caching.Memory.dll
  - Microsoft.Extensions.DependencyInjection.Abstractions.dll
  - Microsoft.Extensions.Options.dll

## [1.0.0] - 2022-03-22

### Added
- Created the first version of the package.
