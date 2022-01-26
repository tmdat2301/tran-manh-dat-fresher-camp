# tran-manh-dat-fresher-camp
 Bài tập chia theo từng branch.
# Go Ex4 (Question)
 Vì sao trong khoá học này các bạn được khuyên không nên dùng khoá ngoại (FK), điểm yếu của khoá ngoại là gì?
# Answer:
-Performance : 
Having active foreign keys on tables improves data quality but hurts performance of insert, update and delete operations.
-We should not use foreign keys to enhance functionality, edit, delete data. Use foreign keys only in cases where the data needs to be consistent with each other.
