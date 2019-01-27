# WP Content Framework (Upgrade module)

[![License: GPL v2+](https://img.shields.io/badge/License-GPL%20v2%2B-blue.svg)](http://www.gnu.org/licenses/gpl-2.0.html)
[![PHP: >=5.6](https://img.shields.io/badge/PHP-%3E%3D5.6-orange.svg)](http://php.net/)
[![WordPress: >=3.9.3](https://img.shields.io/badge/WordPress-%3E%3D3.9.3-brightgreen.svg)](https://wordpress.org/)

[WP Content Framework](https://github.com/wp-content-framework/core) のモジュールです。

# 要件
- PHP 5.6 以上
- WordPress 3.9.3 以上

# インストール

``` composer require wp-content-framework/upgrade ```  

## 依存モジュール
* [common](https://github.com/wp-content-framework/common)

## 関連モジュール
* [presenter](https://github.com/wp-content-framework/presenter)
  * 更新情報を表示する場合に必要です。

## 基本設定
- configs/config.php  

|設定値|説明|
|---|---|
|update_info_file_url|更新チェックを行うファイルのURLを設定|
|readme_file_check_url|Upgrade Noticeを取得するreadmeファイルのURLを設定|

- configs/setting.php  

|設定値|説明|
|---|---|
|check_update|開発バージョンをチェックするかどうか|

# Author

[technote-space](https://github.com/technote-space)
