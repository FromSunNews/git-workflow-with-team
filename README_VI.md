![image](https://github.com/FromSunNews/git-workflow-with-team/assets/111409554/cce93af4-e03b-4b1e-ad78-7910f5997f8c)
# Giới Thiệu 
- master: master hay main được hiểu là nhánh chính khi chúng ta bắt đầu một dự án. Quy tắc: ở nhánh master chúng ta sẽ không chỉnh sửa code trực tiếp mà sẽ push qua nhánh khác (hạn chế được lỗi ở master)
- develop: là nhánh phát triển các tính năng cụ thể. Ở nhánh develop sẽ được chia ra thành từng fearture nhỏ sau đó sẽ gộp lại về develop. 
- release: là nhánh xuất bản chịu trách nhiệm tổng hợp các code từ nhánh develop và sau đó đẩy code qua nhánh master
- hotfixes: là nhánh chịu trách nhiệm cho việc sửa lỗi nhanh khi sản phẩm có lỗi trong quá trình triển khai cho người dùng. Sau khi sửa lỗi xong hotfixes sẽ đưa về master để triển khai production, đồng thời sẽ chuyển về develop để sửa lỗi đang tồn tại trong nhánh develop
- production: trong hình sẽ không có nhánh này bời vì thường triển khai code sẽ trên nhánh master. Giống như khi deploy code FE lên vercel, vercel sẽ là nhánh master làm nhánh chính để triển khai code cho người dùng.
- feature: là các nhánh nhỏ từ develop, nhánh này chịu trách nhiệm phát triển các tính năng nhỏ. Sau khi tính năng hoàn thành sẽ đẩy code qua nhánh develop
  
