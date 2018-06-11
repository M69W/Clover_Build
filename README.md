# Clover_Build
本仓库自动部署，`CLOVER`源码有更新时，此脚本会自动部署并上传`CLOVERX64.efi`、`iso`和`zip`至本仓库`build`目录

# Notes
`GitHub`部署速度可能跟不上，当发现源码有更新但本仓库没有及时跟进时，请前往`Gitee`找相应仓库，[传送门](https://gitee.com/athlonreg/Build_Clover)

## Credits
- `Clover Team`
- [vit9696's AptioFixpkg](https://github.com/vit9696/AptioFixPkg)
- zenith432
- Micky1979

## Changelog
- 4532: sync edk2 svn r27295; update build_rule.txt by zenith432 -- 2018-06-11
 
- 4531: fix theme and dsdt submenu handling by slice2009 -- 2018-06-11
 
- 4530: correct folder moving (stupid xcode) by slice2009 -- 2018-06-11
 
- 4528: update package by vector sigma by slice2009 -- 2018-06-11
 
- 4527: reverted back UDK2018 patches by slice2009 -- 2018-06-11
 
- 4526: special way for hibernation on INSYDE UEFI BIOS by slice2009 -- 2018-06-11
 
- 4525: fix package _title and _description, by vector sigma by slice2009 -- 2018-06-10
 
- 4524: working Base.h for UDK2018 by slice2009 -- 2018-06-10

- 4523: an attempt to cure hibernation in a case of two HDD by slice2009 -- 2018-06-09
 
- 4522: fix hibernation issue when two drives in system by slice2009 -- 2018-06-08
 
- 4521: corrected switch menu navigation by slice2009 -- 2018-06-07
 
- 4519: additional patches for mojave by PMheart by slice2009 -- 2018-06-06
 
- 4513: choices for mandatory drivers by slice2009 -- 2018-06-03
 
- 4512: fix previous commit by slice2009 -- 2018-06-01
 
- 4510: fix PS2Keyboard by Jief Machak by slice2009 -- 2018-05-30
 
- 4509: exclude pointers to milk by slice2009 -- 2018-05-30
 
- 4508: exclude null chars from generated config.plist by slice2009 -- 2018-05-29
 
- 4507: correct mistakes by slice2009 -- 2018-05-29

- 4506: correct makeiso for new drivers location by slice2009 -- 2018-05-28
 
