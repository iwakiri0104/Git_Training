
# **Git_Training2023**
Here is craid's Git_Training2023 repository.

## **Install**
how to clone repository.
```
cd $WORKDIR
git clone　git@github.com:iwakiri0104/Git_Training2023.git
```

## **目的**
Git課題では、これまで学んだGitの知識を活用して、**Gitflowの概念を元に**、実務でのGitの使い方を、より実践的に学ぶことを目的とします。

Gitflowは、Gitのブランチ管理と作業フローを効率化する方法です。
主要ブランチ（master, development, feature）を活用して、開発中のコードと安定したリリースバージョンを分けて管理します。機能開発やバグ修正はfeatureブランチで行い、問題なければdevelopmentブランチにマージ。
最終的に安定化したら、masterブランチにマージしてリリースします。Gitflowを利用することにより、チーム開発の効率向上やバージョン管理のスムーズ化が期待できます。


- 参考サイト
    - [Gitflow ワークフロー](https://www.atlassian.com/ja/git/tutorials/comparing-workflows/gitflow-workflow)

## **開発課題の進め方**
### 1. 個人用の作業ブランチを作成する

- ブランチ名
    - feature/{日付}_{名前}　例) feature/20230411_Yamada

developmentブランチからfeatureブランチを作成してください。
  　
  
### 2. 自己紹介文を記入する
- /public_html/index.html
  - 自身の**名前が記載された作業スペース**で、ご自身の名前と自己紹介文を記入してください
    - 自己紹介文に指定はありません。自由にご記入ください。一言でもかまいません。
    - 写真は必須ではありませんが、余力があれば加えていただいても構いません。


※作業スペースは名前ごとにコメントアウトで指定しています。

例)
```
        <!--yamada-san start--->

        <!--yamada-san end--->
```


### 　3. 作業が完了したらリモートブランチへpushする
- 必要なgit commandを使ってリモートへpushしてください

### 　4. developmentブランチへPRを作成
- 作ったブランチをDevelopmentブランチへPR

※Googleフォームで回答を提出後、作成していただいたPRに対してコメントで指示を出します。内容に従って修正をしていただき、その後再度pushしていただきます。


## **完了定義**
- developmentブランチからfeatureブランチを作成できている
- 作成したfeatureブランチ内で修正を加えることができている
- featureブランチをremoteにpushすることができている
- Developmentブランチに対してPull Requestを作成することができている
- Pull Requestに対してコメントされた内容を元に修正をすることができている
