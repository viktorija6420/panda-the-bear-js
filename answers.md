<!-- 1. Select the element that contains the profile image (hint: look for the class). Change the src attribute so it points to a picture of your choosing instead. -->

var pictureParent = document.querySelector('.highlight');
undefined

pictureParent

var picture = document.querySelector('img');

picture.src = 'https://placebear.com/400/400'

<!-- 1. Use the same approach to select the element that contains the photo of the sky and change the src attribute to another picture URL of your choosing. -->

var picturesAll = document.querySelectorAll ('img') ;
picturesAll;
picturesAll[1].src = 'https://placebear.com/325/225';

<!-- 2. Select the heading that says "Panda the Bear" and change it to your own name. -->
var u = document.querySelectorAll('span');
u[1];
u[1].innerText = 'Viktorija';

<!-- 3. Select the heading that says "Employment" and change it to something else. (hint: use a descendant selector) -->
v = document.querySelector('#employment .info-title');
v.innerText = 'Hobbies';

<!-- 4. Change the colour of the body. -->
var f = document.querySelector('body');
f.style.backgroundColor = 'red';

<!--5. Change the colour of each element using the highlight class. Use a for loop to do this. -->
var j = document.querySelectorAll('.highlight')
  for (var i=0; i<j.length; i++) {
  j[i].style.backgroundColor = 'yellow'

}

<!-- 6. Change the font family of the h1 to 'monospace'. -->
var h =document.querySelector('h1');
h.style.fontFamily = 'monospace';

<!-- 7. Find a way to select the round icons in the sidebar and then change their colour. -->
l = document.querySelectorAll('.action-icon-container' '.action-icon-bg');
for (var i=0; i<l.length; i++) {
    l[i].style.backgroundColor = 'purple'
};

<!-- 8. Scroll down to the contact form. Change the placeholder attribute of the name field to "identify yourself". -->
ll = document.querySelector('#name');
ll.placeholder = 'Identify yourself';

<!-- 9. Change the placeholder attribute of the message field to "state your business". -->
mm = document.querySelector('#message');
mm.placeholder = "State your business.";

<!-- 10. Give the name field a "value" attribute of "your nemesis". -->
cc = document.querySelector('#name');
cc.defaultValue = 'Your namesis.';

<!-- 11. Change the value attribute of the email field to "koalathebear@gmail.com". -->
zz = document.querySelector('#email');
zz.defaultValue =
"koalathebear@gmail.com";

<!-- 12. Change the value of the submit button on the contact form to "En garde!". -->
ss = document.querySelector('#submit');
ss.defaultValue =
"En garde!";

<!-- 13. We should stop Koala from sending an email to Panda that they might regret! Find a way to disable the submit button (hint: familiarize yourself with the disabled attribute). -->
ss = document.querySelector('#submit');
ss.disabled = true;

<!-- 14. We should help Panda protect their privacy by erasing their personal details from the sidebar. -->
qq = document.querySelector('.bio-.info);
qq.hidden = true;
