Assignment 1

1. var profilePic = document.body.querySelector('img');
   profilePic.src = 'https://static.giantbomb.com/uploads/square_medium/15/155548/2353605-pandaman.png';

1. var body = document.body;
   var section = body.querySelector('section');
   var sky = section.querySelector('img');
   sky.src = 'http://cdn.newsapi.com.au/image/v1/fbea7b3a223c746aca3104e2cf942ec6?width=650';

2. var heading = section.querySelector('.highlight');
   heading.innerText = 'Brandon Levy';

3. var employment = section.querySelector('#employment');
   var h3 = employment.querySelector('h3');
   var test = h3.innerHTML;
   var new_test = test.replace("Employment", "Test");
   h3.innerHTML = new_test;

4. body.style.backgroundColor = 'red';

5. var highlights = body.querySelectorAll('.highlight');
   for(i=0;i<highlights.length;i++){highlights[i].style.color = 'blue'};

6. var h1 = body.querySelectorAll('h1');
   h1.forEach(function(h1){h1.style.fontFamily = 'monospace'});

7. var icons = body.querySelectorAll('.action-container > .action-icon-container');
   icons.forEach(function(icon){icon.querySelector('a').style.backgroundColor = 'red'});

8. body.querySelector('#name').placeholder = "identify yourself";

9. body.querySelector('#message').placeholder = "state your business";

10. body.querySelector('#name').value = "your nemesis";

11. body.querySelector('#email').value = "koalathebear@gmail.com";

12. body.querySelector('#submit').value = "En garde!";

13. body.querySelector('#submit').disabled = true;

14. var bio = body.querySelector('.bio-info');
    bio.hidden = true;


Assignment 2

1.  var timeTravel = body.querySelector('#time-travel');
    var timeTravelParent = timeTravel.parentNode;
    timeTravelParent.parentNode.removeChild(timeTravelParent);

2.  var pikachu = body.querySelector('#right-image > img');
    var pikachu2 = pikachu.cloneNode(true);
    var portfolioContainer = body.querySelector('.portfolio-container');
    portfolioContainer.appendChild(pikachu2);

3. for(i=0;i<10;i++){portfolioContainer.appendChild(pikachu.cloneNode(true))};

4. var listItem = document.createElement('li');
   var leftSpan = document.createElement('span');
   var lastUpdated = document.createTextNode('Page last updated on');
   leftSpan.appendChild(lastUpdated);
   listItem.appendChild(leftSpan);
   var rightSpan = document.createElement('span')
   var dateUpdated = document.createTextNode(new Date);
   rightSpan.appendChild(dateUpdated);
   listItem.appendChild(rightSpan);
   var bio = body.querySelector('.bio-info');
   bio.appendChild(listItem);
