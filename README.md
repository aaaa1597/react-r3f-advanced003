# react-r3f-advanced003
React+TypeScript+R3Fのtutorial応用編3(glTFで3Dモデルとモーションデータ読込み)

![](https://storage.googleapis.com/zenn-user-upload/26951f09783d-20240104.png)

# ポイント
3Dモデルのアニメーションを実行するには、THREE.AnimationMixerを使うのがポイント。<br/>
THREE.AnimationMixerの使い方は、以下の通り。<br/>

1.　new THREE.AnimationMixer() ← 引数にsceneを渡す。<br/>
 ↓<br/>
2. clipAction()で、THREE.AnimationMixerにアニメーション追加<br/>
 ↓<br/>
3. 追加したアニメーションをstart()<br/>
 ↓<br/>
4. useFrame()の中で、mixer.update()<br/>
で動くようになる。分かりやすっ!!
