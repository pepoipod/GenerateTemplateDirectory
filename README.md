# GenerateTemplateDirectory

Unity Projectのテンプレートフォルダを自動生成してくれるEditor拡張です。

## Set up

GenerateTemplateDirectory.unitypackageを任意のProjectにインポートしてください。

## Usage

### Projectのテンプレートを作成

Projectビュー上で右クリックして `Generate Assets Template Directory` を選択して下さい。    
以下のディレクトリ構成が構築されます。
    
```
Assets
├── Common
│   ├── Animations
│   ├── Audios
│   ├── Materials
│   ├── Plugins
│   ├── Prefabs
│   ├── Scenes
│   ├── Scripts
│   └── Textures
└── Resources
```

### Sceneフォルダのテンプレートを作成

テンプレートを生成したいフォルダをProjectビュー上で右クリックして `Generate Assets Template Directory` を選択して下さい。    
以下のディレクトリ構成が構築されます。
   

```
選択したフォルダー
├── Animations
├── Audios
├── Materials
├── Plugins
├── Prefabs
├── Scenes
├── Scripts
└── Textures
```