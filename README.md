# easy-ui-templates

## サマリ
よく使うUIのテンプレートをまとめたパッケージ。

## 導入手順
zipでダウンロードし、package/EasyUITemplates.packageをプロジェクトにインポート。

## 仕様
現在はタブとスクロールの二つのテンプレートがある。
それぞれの使用について説明する。

### タブ
#### 動作確認
Sample/TabSample

#### シーンへの配置
Canvas以下にPrefabs/Tabを配置

#### カスタマイズ手順
Tab.prefabをシーンに配置したらインスタンスを右クリックし、UnpackPrefabを行う。
Tab以下のcontent以下を編集することでデザインを変更する。

### スクロール
#### 動作確認
Sample/ScrollSample

#### シーンへの配置
Canvas以下にPrefabs/Scrollを配置

#### カスタマイズ手順
Scroll.prefabをシーンに配置したらインスタンスを右クリックし、UnpackPrefabを行う。
content以下のElementの子要素を編集することでデザインを変更する。

### 開発手順
#### 開発環境
Unity2019.1.1f
標準機能のみで作成したため特に外部依存性はない。

### Package

#### Package出力先
package/EasyUITemplates.package

#### Package出力手順
packageとして出力するディレクトリ:
easy-ui-templates/dev/Asset/EasyUiTemplate以下

