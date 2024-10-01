# 遊戲背包管理系統
建立一個簡易的遊戲背包資料儲存系統，儲存遊戲背包中的寶可夢、隊伍列表與道具

## 使用到的資料結構
1. Heap：儲存寶可夢物件、隊伍物件
2. AVL tree：儲存寶可夢資訊，包含其名稱、個性、屬性、身高、體重
3. m-way tree：儲存隊伍資訊，包含隊伍名稱、內含多少隻寶可夢
4. linked-list：儲存隊伍中的寶可夢(pokemon_in_team)資訊
5. queue：儲存道具
6. Binary Tree：儲存以關鍵字搜尋(中序搜尋)時符合條件的寶可夢物件
7. stack：儲存以關鍵字搜尋(前序搜尋)時符合條件的隊伍物件

## 系統功能
1. 新增：
新增Pokemon／新增隊伍
2. 刪除：
刪除Pokemon／刪除隊伍
3. 編輯：
將Pokemon新增到隊伍中／將Pokemon從隊伍中刪除／編輯隊伍名稱
4. 道具：
新增道具／刪除即期道具／列出所有道具／刪除所有道具
5. 展示：
列出所有Pokemon／列出所有隊伍／列出隊伍中的Pokemon
6. 搜尋
利用名稱搜尋Pokemon／利用屬性搜尋Pokemon／搜尋隊伍
7. 離開(離開系統)


