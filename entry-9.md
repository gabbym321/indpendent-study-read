# Last entry

## What I did this week: 
This week was hard because it was my last week to get everything together. I had to rush a little because previous weeks I have been sick and unable to work on my project. What I did was made the final touches on my project and got it to work. At first it was giving trouble because although everything appeared to be working, when I looked at my email nothing appeared. The reason my project seemed to be working well was when I pressed submit it sent me to a page confirming that the email was sent correctly. Once I looked it up I found out some information I didn’t know before. I learned that over a million emails get sent a day but a lot of them are spam. So what I needed to do was make a filter that confirms that this email is valid to go through. I learned that there were two thing that do this: SMPT and PHPmailer. Due to the fact that I am writing in PHP, I decided to use PHPmailer. Installing this confused me at first. I had to look at a lot of websites and videos to figure it out. It was almost like installing an API to code. I found a github page that had the verifications needed and I followed along to a video that explained everything. I’ve looked up the code and tutorials on how to make that happen and completed it. 

## What I need to do to finish everything up tomorrow:
 
Tomorrow is my last day to work on this project before the presentations. What I plan to do is fix up a google slide with diagrams and practice what I am going to say out loud to the class. I will then try to add some CSS to my project just to make sure it looks nice. Then I will be done. 

## Evidence of learning: 

``"phpmailer/phpmailer": "~6.0"`` This is the code I needed to type in to use PHPmailer <br> <br> 


``// These must be at the top of your script, not inside a function
use PHPMailer\PHPMailer\PHPMailer;
use PHPMailer\PHPMailer\Exception;

//Load Composer's autoloader
require 'vendor/autoload.php';

$mail = new PHPMailer(true);                              // Passing `true` enables exceptions
try {
    //Server settings
    $mail->SMTPDebug = 2;                                 // Enable verbose debug output
    $mail->isSMTP();                                      // Set mailer to use SMTP
    $mail->Host = 'smtp1.example.com;smtp2.example.com';  // Specify main and backup SMTP servers
    $mail->SMTPAuth = true;                               // Enable SMTP authentication
    $mail->Username = 'user@example.com';                 // SMTP username
    $mail->Password = 'secret';                           // SMTP password
    $mail->SMTPSecure = 'tls';                            // Enable TLS encryption, `ssl` also accepted
    $mail->Port = 587;                                    // TCP port to connect to
`` This was a lot but here is the code I needed to put in my file in order to tell the email that it is okay to send and accept the emails I am making with PHP.  <br> <br> 
My learning was shown a lot in my research trying to figure out why my emails were not sending. Although this code was explained in a video, the more important part was understanding why I was doing it. There is a certain authercation that needs to be used because of the amount of spam mail emails received every day. 

## Takeaways: 
When something is not working and you don't know why, ask specific questions on google. 
Things are not going to work the first time you try it. Make a bunch of files and keep testing things. Learn from your previous mistakes and make things better. 
