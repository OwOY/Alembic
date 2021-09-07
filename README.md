# Alembic

1. 建立Model
2. alembic upgrade head  #更新至最新資料庫(確認)
3. alembic revision --autogenerate -m "describe"   #Commit資料庫 (#只能用"不能用'#)
4. alembic upgrade head  #更新至最新資料庫(更新)
