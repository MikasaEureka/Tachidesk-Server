# Server: v0.4.8-next + WebUI: r767
## Tachidesk-Server
### Public API
#### Non-breaking changes
- N/A

#### Breaking changes
- (r857) renamed: `SourceDataClass.isNSFW` -> `SourceDataClass.isNsfw`

#### Bug fixes
- N/A

### Private API
- (r850) Bump WebUI version to r767
- (r861) Bump WebUI version to r769

#### Non-code changes
- (r851) Add this changelog file and `CHANGELOG-TEMPLATE.md`
- (r852-r853) `CONTRIBUTING.md`: Add a note about this maintaining this file changelog
- (r855) `CONTRIBUTING.md`: text cleanup
- (r859) `CONTRIBUTING.md`: remove dumb rule
- (r862) `windows-bundler-sh`: update jre


## Tachidesk-WebUI
#### Visible changes
- (r767-r769) Support for hiding NSFW content in settings screen, extensions screen, sources screen

#### Bug fixes
- N/A

#### Internal changes
- (r767) Remove some duplicate dependency declaration from `package.json`

#### Non-code changes
- (r42-r45) Change `README.md`: some links and stuff 
- (r45-r765) Add all of the commit history from when WebUI was separated from Server, jumping from r45 to r765 (r45 is exactly the same as r765)
- (r766) Steal `.gitattributes` from Tachidesk-Server
- (r767) Dependency cleanup in `package.json`




# Server: v0.4.8 + WebUI: r41
## Tachidesk-Server
### Public API
#### Non-breaking changes
- Added support for serializing Search Filters
- `SourceDataClass` now has a `isNsfw` key

#### Breaking changes
- N/A

#### Bug fixes
- Fixed a bug where backup restore reversed chapter order
- Open Site feature now works properly (https://github.com/Suwayomi/Tachidesk-WebUI/issues/19)

### Private API
- Added `CloudflareInterceptor` from TachiWeb-Server
- Restoring backup for mangas in library(merging manga data) is now supported

## Tachidesk-WebUI
#### Visible changes
- Better looking manga card titles
- Better reader title, next, prev buttons

#### Bug fixes
- Open Site feature now works properly (https://github.com/Suwayomi/Tachidesk-WebUI/issues/19)
- Re-ordering categories now works

#### Internal changes
- N/A