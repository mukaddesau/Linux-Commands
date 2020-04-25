#  Common Commands Cheatsheet
## Git Commands
1. mkdir <my_directory>

    // Create a new directory // Yeni bir klasör oluştur

2. cd <my_directory> 

    // Go to the directory // Oluşturduğun klasörün içine git

3. git init

    //  Create a ".git" directory (not a file) which turns your directory into a git repository. 
   
    // ".git" klasörü oluşturarak kendi klasörünü git deposuna dönüştür. (Bu sayede klasöründekileri uzak depoya gönderip her farklı versiyonuyla kaydedebilirsin.)
   
    // ".git" directory consists of commit logs and configuration info etc. 
 
    // ".git" klasörü kısaca, kaydettiğin farklı versiyonların bilgisini ve senin github repolarına ait bilgileri vb. tutar diyebiliriz.

4. ls -la
 
    // Show not only visible but also hidden contents of the current directory Check whether the ".git" directory exists.
    
    // Klasörün git deposuna dönüşmesi için oluşması gereken gizli ".git" klasörünün oluşup oluşmadığını kontrol et
    
    ![Git Klasörü İçerik]("https://github.com/mukaddesau/Linux-Commands/Pictures/git_content.png")
    
5. Open your repositories from browser <https://github.com/user_name?tab=repositories> 

6. Create "New" repository. 
7. git remote add origin <https://github.com/user_name/user_repo.git> 

// Github remote repository is identified with your directory. 

// Github uzak depo ile lokaldeki klasörünü ilişkilendir. 

* m
