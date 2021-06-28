# UnityColoredObjMeshAttach
Thanks : https://github.com/shimawork/unity-vertex-color-obj-loader

1. Objをunityインポート
2. インポートしたObject->Model->read/write enableにチェック
3. Edit->Project Setting->Graphics->Always Included ShadersにShaderを登録
4. Object->default(meshがある方)にC#コードをアタッチ
※ faceの形式は ```f xx//xx pp//pp kk//kk``` の形に対応しています
