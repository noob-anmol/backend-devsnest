### fs module  

#### Commands:  
* `fs.mkdirSync("dirname")`  
* `fs.writeFileSync("filepath", "content", callback)`  --> write file  
* `fs.appendFileSync("filepath", "content")`  --> update file content  
* `var data = fs.readFileSync("filepath", "utf-8")`  --> read file  
* `fs.renameSync("filename", "new_name_of_file")`  --> rename file  
* `fs.unlinkSync("filepath")` --> remove/delete file  
* `fs.rmdirSync("dirname")`  --> remove directory  