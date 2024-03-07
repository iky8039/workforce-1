手元で作る場合のパターン
1. git init <--- すべての始まり (デフォルトブランチmainが自動的に作成される)
2. git commit <-- mainへの歴史の追加
3. git commit <-- mainへの歴史の追加
4. git remote add origin github.com/hoge/poge.git <-- 手元の main ブランチの upstream に "origin" を追加 (==GitHub)
5. git push -u origin main <--- 手元のmainの「歴史」を "origin" (GitHub) の main へ push 
  これが許されるのは origin (GitHub) 上に main の歴史が何もない場合のみ （README.md とか一つでも作ったらアウト）
　どうしても手元にある main の歴史で全てを上書きしたければ push -f を使う
