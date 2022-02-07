<?php

$mysqli = mysqli_connect('localhost:3306','root','','carts-121');
if(isset($_POST['add_Student'])){

   $student_name = $_POST['student_name'];
   $passport_number = $_POST['passport_number'];
   
   $date_of_birth = $_POST['date_of_birth'];
   $student_email = $_POST['student_email'];
   $student_tele = $_POST['student_tele'];
   $student_order = $_POST['student_order'];
   $passport_or = $_FILES['passport_or']['$passport_or'];
   $Student_tmp_passport_or = $_FILES['passport_or']['tmp_passport_or'];
   $Student_passport_or = 'passports/'.$passport_or;
   $passport_tr = $_FILES['passport_tr']['$passport_tr'];
   $Student_tmp_passport_tr = $_FILES['passport_tr']['tmp_passport_tr'];
   $Student_passport_tr = 'passports/'.$passport_tr;
   $certificate__or = $_FILES['certificate__or']['$certificate__or'];
   $Student_tmp_certificate__or = $_FILES['certificate__or']['tmp_certificate__or'];
   $Student_certificate__or = 'certificates/'.$certificate__or;

   $certificate__tr = $_FILES['certificate__tr']['$certificate__tr'];
   $Student_tmp_certificate__tr = $_FILES['certificate__tr']['certificate__tr'];
   $Student_certificate__tr = 'certificates/'.$certificate__tr;


   $other = $_FILES['other']['$other'];
   $Student_tmp_other = $_FILES['other']['certificate__tr'];
   $Student_other = 'other/'.$other;




   
   if(empty($student_name) || empty($passport_number)
       || empty($date_of_birth) || empty($student_email) || empty($student_tele)
       || empty($student_order) || empty($passport_or) || empty($passport_tr)
       || empty($certificate__or) || empty($certificate__tr)){
      $message[] = 'please fill out all';
   }else{
      $insert = "INSERT INTO students(name, passport_number, date_of_birth, student_email, student_tele, student_order, passport_or, passport_tr,
      certificate__or, certificate__tr, other) 
      VALUES('$student_name', '$passport_number', '$date_of_birth'
      , '$student_email' , '$student_tele' , '$student_order'
      , '$passport_or' , '$passport_tr' , '$certificate__or'
      , '$certificate__tr') ,'$other')";


       $upload = mysqli_query($mysqli,$insert);

       if($upload){
         $message[] = 'new product added successfully';
      }else{
         $message[] = 'could not add the product';
      }
   }

};

?>


<!DOCTYPE html>
<html lang="en">
<head>
   <meta charset="UTF-8">
   <meta http-equiv="X-UA-Compatible" content="IE=edge">
   <meta name="viewport" content="width=device-width, initial-scale=1.0">
   <title>admin page</title>

   <!-- font awesome cdn link  -->
   <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/5.15.4/css/all.min.css">

   <!-- custom css file link  -->
   <link rel="stylesheet" href="css/style.css">

</head>
<body>

<?php

if(isset($message)){
   foreach($message as $message){
      echo '<span class="message">'.$message.'</span>';
   }
}

?>
   
<div class="container">

   <div class="admin-product-form-container">
   <form action="<?php $_SERVER['PHP_SELF'] ?>" method="post" enctype="multipart/form-data">
         <h3>New Student</h3>
         <input type="text" placeholder="enter student name" name="student_name" class="box">
         <input type="text" placeholder="enter passport number" name="passport_number" class="box">
         <input type="text" placeholder="enter date of birth" name="date_of_birth" class="box">
         <input type="text" placeholder="enter your email" name="student_email" class="box">
         <input type="text" placeholder="enter phone number" name="student_tele" class="box">
         <input type="text" placeholder="enter the order" name="student_order" class="box">

         
         <h1>original passport</h1>
         <input type="file" accept="image/png, image/jpeg, image/jpg ,image/pdf" name="passport_or" class="box">
         <h1>translation of passport</h1>
         <input type="file" accept="image/png, image/jpeg, image/jpg ,image/pdf" name="passport_tr" class="box">
         <h1>original certificate</h1>
         <input type="file" accept="image/png, image/jpeg, image/jpg ,image/pdf" name="certificate__or" class="box">
         <h1>translation of the certificate</h1>
         <input type="file" accept="image/png, image/jpeg, image/jpg ,image/pdf" name="certificate__tr" class="box">
         <h1>other documents</h1>
         <input type="file" accept="image/png, image/jpeg, image/jpg ,image/pdf" name="other" class="box">
         <input type="submit" class="btn" name="add_Student" value="add student">
      </form>

   </div>

   <div class="product-display">
      <table class="product-display-table">
         <thead>
         <tr>
            <th>Student Name</th>
            <th>Student University</th>
            <th>status</th>
            <th>action</th>
         </tr>
         </thead>
      </table>
   </div>

</div>


</body>
</html>