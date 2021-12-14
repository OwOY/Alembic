# Alembic

1. 建立Model
2. alembic revision --autogenerate -m "describe"   #Commit資料庫 (#只能用"不能用'#)
3. alembic upgrade head  #更新至最新資料庫(更新)

- 升級版本
```
alembic upgrade head
```
- 降級版本
```
alembic downgrade -1
```
- 查看歷史紀錄
```
alembic history
```
- 新增migration
```
alembic revision --autogenerate -m "descirbe"
```
- 指定config
```
alembic -c test1.ini history
```

# 更多延伸閱讀
```
https://codertw.com/%E7%A8%8B%E5%BC%8F%E8%AA%9E%E8%A8%80/35715/
```
