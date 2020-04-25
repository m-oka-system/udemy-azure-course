# Chapter6.仮想マシンスケールセットを使ってみよう

## 参考サイト

- [Azure ポータルからDSCを設定する](https://docs.microsoft.com/ja-jp/azure/virtual-machines/extensions/dsc-overview#azure-portal-functionality)

- [Azure Desired State Configuration 拡張機能のバージョン履歴](https://docs.microsoft.com/ja-jp/powershell/dsc/getting-started/azureDscexthistory)

- [自動スケールのスケールルールについて](https://blogs.msdn.microsoft.com/jpcie/?p=1315)

## コマンド集

#### PowershellDSC拡張機能の入力項目
```powershell
# Module-qualified Name of Configuration
WindowsWebServer.ps1\IISInstall

# Version
2.76
```

#### CPU100%にするコマンド

```powershell
while ($true) {}
```

## VMSS作成手順(2020年4月時点)

仮想マシン作成時と同じように基本情報を入力する。
イメージはあらかじめ作成(日本語化)しているカスタムイメージを選択する。

![VMSSの作成-基本](https://user-images.githubusercontent.com/22112831/80272531-80942480-8705-11ea-95b5-44254e1975e3.png)

<img src=https://user-images.githubusercontent.com/22112831/80272531-80942480-8705-11ea-95b5-44254e1975e3.png width=70%>