路径 F:/xiaoji/

xiaoji.db 更新游戏下载路径
sqlite3.exe xiaoji.db
UPDATE Gameinfo SET FilePath = replace( FilePath, 'F:\Simulate', 'F:\xiaoji\Simulate')