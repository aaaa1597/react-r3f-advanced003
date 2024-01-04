# react-r3f-advanced003
React+TypeScript+R3Fのtutorial応用編3(glTFで3Dモデルとモーションデータ読込み)

![](https://storage.googleapis.com/zenn-user-upload/26951f09783d-20240104.png)

# ポイント
3Dモデルのアニメーションを実行するには、THREE.AnimationMixerを使うのがポイント。
THREE.AnimationMixerの使い方は、以下の通り。

1.　new THREE.AnimationMixer() ← 引数にsceneを渡す。
 ↓
2. clipAction()で、THREE.AnimationMixerにアニメーション追加
 ↓
3. 追加したアニメーションをstart()
 ↓
4. useFrame()の中で、mixer.update()
で動くようになる。分かりやすっ!!


