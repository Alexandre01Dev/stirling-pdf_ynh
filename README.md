<!--
N.B.: This README was automatically generated by <https://github.com/YunoHost/apps/tree/master/tools/readme_generator>
It shall NOT be edited by hand.
-->

# Stirling PDF for YunoHost

[![Integration level](https://dash.yunohost.org/integration/stirling-pdf.svg)](https://ci-apps.yunohost.org/ci/apps/stirling-pdf/) ![Working status](https://ci-apps.yunohost.org/ci/badges/stirling-pdf.status.svg) ![Maintenance status](https://ci-apps.yunohost.org/ci/badges/stirling-pdf.maintain.svg)

[![Install Stirling PDF with YunoHost](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=stirling-pdf)

*[Read this README in other languages.](./ALL_README.md)*

> *This package allows you to install Stirling PDF quickly and simply on a YunoHost server.*  
> *If you don't have YunoHost, please consult [the guide](https://yunohost.org/install) to learn how to install it.*

## Overview

This is a robust, locally hosted web-based PDF manipulation tool. It enables you to carry out various operations on PDF files, including splitting, merging, converting, reorganizing, adding images, rotating, compressing, and more. This locally hosted web application has evolved to encompass a comprehensive set of features, addressing all your PDF requirements.

### Features

- Dark mode support.
- Custom download options
- Parallel file processing and downloads
- Custom 'Pipelines' to run multiple features in a queue
- API for integration with external scripts
- Optional Login and Authentication support (see here for documentation)
- Database Backup and Import (see here for documentation)


**Shipped version:** 0.29.0~ynh1

**Demo:** <https://stirlingpdf.io/>

## Screenshots

![Screenshot of Stirling PDF](./doc/screenshots/screenshot.jpg)

## Documentation and resources

- Official app website: <https://www.stirlingpdf.com/>
- Official user documentation: <https://docs.stirlingpdf.com/>
- Official admin documentation: <https://github.com/Stirling-Tools/Stirling-PDF/blob/main/LocalRunGuide.md>
- Upstream app code repository: <https://github.com/Stirling-Tools/Stirling-PDF>
- YunoHost Store: <https://apps.yunohost.org/app/stirling-pdf>
- Report a bug: <https://github.com/YunoHost-Apps/stirling-pdf_ynh/issues>

## Developer info

Please send your pull request to the [`testing` branch](https://github.com/YunoHost-Apps/stirling-pdf_ynh/tree/testing).

To try the `testing` branch, please proceed like that:

```bash
sudo yunohost app install https://github.com/YunoHost-Apps/stirling-pdf_ynh/tree/testing --debug
or
sudo yunohost app upgrade stirling-pdf -u https://github.com/YunoHost-Apps/stirling-pdf_ynh/tree/testing --debug
```

**More info regarding app packaging:** <https://yunohost.org/packaging_apps>
