# Entry week 5 
## What I did this week: 
### This week consisted of a lot of tinkering. I was able to figure out how to run PHP in cloud 9. Usually I just have to press preview at the top and my work would pop up, but with PHP I had to do something different. I needed to go into the terminal and put in a certain section that PHP is the language I am using. Then it gave a link and I clicked that link and said preview and it showed me the work I was doing. It was hard for me to figure out how to do this because a bunch of the websites I looked at while searching up how to get this to work was using confusing terminology that I didn’t understand. After a while of searching I finally found a site that explained everything in a way that I understood. After I got the preview to work I started looking for little exercises I could do with PHP. I did a few that I will show and explain in the next section then I moved on to learning about post in PHP because I know that this was something I would need to know in order to complete my final project. 

## My Tinkering work: 
### Here is a few things I tinkered with in PHP and an explanation: <br>
 `$argv = [2,4,6,8];
  $sum = $argv[1] + $argv[2];
  print("\nThe sum of $argv[1] and $argv[2] is $sum.");` 
What this piece of code does is it makes an array and it says that the sum is equal to index one plus index two of the array that was made. Lastly it prints out a sentence saying that whatever index one is added to index two is the sum which we stored in a variable. <br>
`$name = "awaken";
if ($name== "Mario" ){
echo "I am $name";
} else {
  echo "That’s not my name!";
}`  <br> 
Here I made a if else statement. I made a variable called name equal to awaken and I said that if the variable name is equal to mario we should see I am (whatever the name is in this case it would have to be Mario). I then made an else statement saying that if the name is not Mario then we should see the sentence “That’s not my name!” on the screen. Because the name was not equal to mario, the sentence “That’s not my name!” is what was shown.  <br>

`if(isset($_POST['name'], $_POST['age'])){
  $name = $_POST['name'];
  $age = $_POST['age'];
  echo "Your name is {$name} and your age is {$age}"; `
`<form action="sandbox.php" method="get">
  <input type="text" name="name" >
  <input type="text" name="age">
  <input type="submit"> ` 
Learning this is what I needed in order to really help me with my final project. As shown, the name that we used in the brackets next to post is the same as the names that we declared in the form that was made. The if statement is saying that if we have a value inside of name we are going to do something with it. What we did with this value is `$_POST`. The name checks that there is a value inside of the form and post is actually declared in the method and determines what we do with the values that the user entered inside of the form. When I enter a name and an age I can see that the values I entered gets posted inside of the console. Later we can actually make the values go other places. 

## Next Steps: 
### I figured out how to use post but the only place I am able to make it go is inside of the console. My plans for next week is to first figure out how to make it appear on the screen in a sentence then start to try and figure out how to send it into an email. 

## Takeaways: 
### 
1. It is one thing to look at other people coding but it it totally different to do it yourself. Do a bunch of tinkering and when you get stuck backtrack and see where you made a mistake so you can remember it for next time. 
2. Sometimes when looking for something online the first results you see may either not be what you are looking for or may not work for you. Try changing key words and looking at a bunch of different websites. 
