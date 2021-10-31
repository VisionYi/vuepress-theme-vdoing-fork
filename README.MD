# vuepress-theme-vdoing-fork
- Clone github project from [vuepress-theme-vdoing](https://github.com/xugaoyi/vuepress-theme-vdoing)
- 這是真實作者的 blog 內容
- 此專案只用於 Dome 樣板主題、測試、發 PR 貢獻 (only on development)
- 主要更新主題的方式為如下： [document](https://doc.xugaoyi.com/pages/793dcb/#%E7%89%88%E6%9C%AC%E5%8D%87%E7%BA%A7)
```shell
npm update vuepress-theme-vdoing -D
```

## Project setup
```shell
# install dependency
npm install # or yarn install

# develop
npm run dev # or yarn dev
```

## 貢獻 PR
1. 切回 master 分支和 Github 首頁切回 master 分支
2. 點擊 `Fetch upstream` -> 點擊 `Fetch and Merge`
    ![image](https://i.ibb.co/S3x2Ldh/PR.jpg)
3. 接這開分支 like: `feat-xxx` or `fix-xxx`
4. 修改 code 和推發分支上這個 repo
5. 到原來作者的專案 repo，點擊發布 PR 就能選到此分支名稱啦！ 也能開始撰寫 PR 內容了。
6. 最好是寄發 e-mail 通知作者盡快查看 PR 內容和合併。
7. PR 被合併和發佈新版本後，回到第一步驟更新 master 分支
8. 切到 `fork-doc` 分支同步更新 master 的內容分支。
   - 根目錄的 README.md 不必更新，這是專屬此 repo 的說明檔。
