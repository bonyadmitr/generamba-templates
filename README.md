# Rambafile example

```ruby
### Headers settings
company: COMPANY_NAME

### Xcode project settings
project_name: PROJECT_NAME
xcodeproj_path: PROJECT_NAME.xcodeproj

### Code generation settings section
## The main project target name
project_target: PROJECT_NAME

## The file path for new modules
project_file_path: PROJECT_NAME/Modules

## The Xcode group path to new modules
project_group_path: PROJECT_NAME/Modules

### Dependencies settings section
podfile_path: Podfile

catalogs:
- 'https://github.com/bonyadmitr/generamba-templates.git'

### Templates
templates:
- {name: viper_dip}
- {name: swifty_viper_2}
```



