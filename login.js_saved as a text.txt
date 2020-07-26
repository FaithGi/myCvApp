var username;	
var password;
var success = document.createElement("success");


function aunthentication(username,password){

    var dbUsername = "faith" ;
    var dbPassword = "1234";
    
    if((username.localeCompare(dbUsername)) && (password.localeCompare(dbPassword)))
    {
     
        location.href = "C:/Users/Faithraesetja/faithApp/src/app/list/CvAssignment.html";
        
       // alert("correct");
    
    }else{
       
         alert("incorrect");
    }
}

function resetCredentials(storeUsername, storePassword){
 
  
    storeUsername = dbUsername;
    storePassword = dbPassword;
   
}

