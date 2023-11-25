# dotnet8_wpf_blazor_example1

Windows Presentation Foundation (WPF) の Blazor アプリを構築する  
https://learn.microsoft.com/ja-jp/aspnet/core/blazor/hybrid/tutorials/wpf?view=aspnetcore-8.0

```
> dotnet --info
.NET SDK:
 Version:           8.0.100
 Commit:            57efcf1350
 Workload version:  8.0.100-manifests.71b9f198

ランタイム環境:
 OS Name:     Windows
 OS Version:  10.0.19045
 OS Platform: Windows
 RID:         win-x64
 Base Path:   C:\Program Files\dotnet\sdk\8.0.100\

インストール済みの .NET ワークロード:
 Workload version: 8.0.100-manifests.71b9f198
表示するインストール済みワークロードはありません。
```

```
dotnet new wpf -o .
dotnet add package Microsoft.AspNetCore.Components.WebView.Wpf --version 8.0.3
```

通常実行
```
dotnet run
```

ホットリロード　※razorの変更がリアルタイムに反映される
```
dotnet watch
```

ビルド　※150MB
```
dotnet publish
```
