# article
#Instalasi dan test program
1. Database (MySql)
	a. akses phpmyadmin
	b. buat database article
	c. import article.sql yang ada di folder article/database/

2. penempatan folder
   letakkan folder article di folder htdocs

3. run program
   akses url : http://localhost/article/posts
 
 
#Test API (Postman)
1. Membuat Article Baru
   URL : http://localhost/article/api/posts
   Method : POST
   Body : x-www-form-urlencoded
   Request : title:<title>
			content:<content>
			category:<category>
			status:<Publish/Draft>

2. Memampilkan Seluruh Article
   URL : http://localhost/article/api/posts
   Method : GET
   
3. Menampilkan article dengan id yang di-request
   URL : http://localhost/article/api/posts
   Method : GET
   Params : id = <id>
   
4. Merubah data article dengan id yang di-request
   URL : http://localhost/article/api/posts
   Method : PUT
   Body : x-www-form-urlencoded
   Request : title:<title>
			content:<content>
			category:<category>
			status:<Publish/Draft>
			id:<id>

5. Menghapus data Article
   URL : http://localhost/article/api/posts
   Method : DELETE
   Body : x-www-form-urlencoded
   Request : id = <id>
	
