# bookshelf-app-back-end
This is a submission from dicoding academy in Belajar Membuat Aplikasi Back-End untuk Pemula class. Through this RestAPI we can do basic actions CRUD

1. Save book
    Method : POST
    URL : /books
    Body Request:
    {
        "name": string,
        "year": number,
        "author": string,
        "summary": string,
        "publisher": string,
        "pageCount": number,
        "readPage": number,
        "reading": boolean
    }
    
2. Get All books
    Method : GET
    URL: /books
    
3. Show detaif of book
    Method : GET
    URL: /books/{bookId}
    
4. Change book's data
    Method : GET
    URL: /books/{bookId}
    Body Request:
    {
        "name": string,
        "year": number,
        "author": string,
        "summary": string,
        "publisher": string,
        "pageCount": number,
        "readPage": number,
        "reading": boolean
    }
    
5. Delete book
    Method : DELETE
    URL: /books/{bookId}
