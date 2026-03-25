https://ameblo.jp/soulimpact20141/entry-12733937073.html

```
# nodejs、npmをインストール 
sudo apt install -y nodejs npm
```
Error

```
sudo apt-get update
```

してから再度試したら行けた。

```
# nをインストール
sudo npm install n -g
```
OK

```
# nからnodejsをインストール
sudo n stable
```

```
btakeshi:~$ node --version
v24.14.1
```
proxyでエラーが出たので

```
export https_proxy=http://ユーザー名:パスワード@プロキシアドレス:ポート番号
npm install -g @google/gemini-cli
```

これでエラーなく終了。gemini

```
btakeshi:~$ gemini
  ▝▜▄     Gemini CLI v0.35.0
    ▝▜▄
   ▗▟▀
  ▝▀


Tips for getting started:
1. Create GEMINI.md files to customize your interactions
2. /help for more information
3. Ask coding questions, edit code or run commands
4. Be specific for the best results
```

```
Do you trust the files in this folder?                                                                                                                                                  
                                                                                                                                                                                        
Trusting a folder allows Gemini CLI to load its local configurations, including custom commands, hooks, MCP servers, agent skills, and settings. These configurations could execute code
on your behalf or change the behavior of the CLI.                                                                                                                                       
                                                                                                                                                                                        
                                                                                                                                                                                        
● 1. Trust folder (btakeshi)                                                                                                                                                            
  2. Trust parent folder (home)                                                                                                                                                         
  3. Don't trust
```



│ ? Get started                                                                                                                                                                              │
│                                                                                                                                                                                            │
│   How would you like to authenticate for this project?                                                                                                                                     │
│                                                                                                                                                                                            │
│   ● 1. Sign in with Google                                                                                                                                                                 │
│     2. Use Gemini API Key                                                                                                                                                                  │
│     3. Vertex AI

1.を選択したままENTERすると、

│  Opening authentication page in your browser.                                                                                                                                              │
│                                                                                                                                                                                            │
│  Do you want to continue?                                                                                                                                                                  │
│                                                                                                                                                                                            │
│  ● 1. Yes                                                                                                                                                                                  │
│    2. No

1. ブラウザが立ち上がって

Googleでログイン画面が出るので、アカウントを選択して、ログインすると、認証成功と出た。ブラウザは閉じてよいと。

.geminiフォルダを削除すると最初から。あとでスクショを取る。

ターミナル側は

You've successfully signed in with Google. Gemini CLI needs to be restarted. Press R to restart, or Esc to choose a different authentication method.

Rで再起動がかかって。使えるようになりました。
