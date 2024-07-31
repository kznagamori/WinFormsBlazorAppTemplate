# WinFormsBlazorAppTemplate
WinForms Blazor アプリ を作成するためのテンプレート

## 使用法

### テンプレートの取得
[WinFormsBlazorApp](https://github.com/kznagamori/WinFormsBlazorAppTemplate/releases/download/v1.0.0/kznagamori.WinFormsBlazorApp.1.0.0.nupkg)
をダウンロードします。

### テンプレートのインストール
ダウンロードしたnugetパッケージをインストールします。
```
dotnet new install kznagamori.WinFormsBlazorApp.1.0.0.nupkg
```

### WinForms Blazor アプリプロジェクトの作成
```
dotnet new winforms-blazor.app -n <プロジェクト名>
```
**例:** `dotnet new winforms-blazor.app -n MyWinFormsBlazor`

### テンプレートのアンインストール
```
dotnet new uninstall kznagamori.WinFormsBlazorApp
```

### ターゲット

net8.0のみをターゲットとしています。

### ビルド

```
dotnet build
```

### リリースビルド

```
dotnet publish -c Release
```

### kznagamori.WinFormsBlazorAppp.X.X.X.nupkgの作成
```
nuget pack .\WinformsBlazorAppTemplate.nuspec
```

