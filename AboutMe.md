# Sai Krishna Pullabhatla
I finished my undergrad at Guru Nanak Institutions Technical Campus in Ibrahimpatnam in computer science engineering. At Accenture, I was a Trust and Safety Associate. My hobbies are playing Badminton and swimming.


[Click here to see my photo](https://github.com/s558962/assignment2-Pullabhatla/blob/main/image.jpg)

-----
# Countries Worth Visiting

| Country |  Reason to Visit  | Days to stay  |
| ------- |  ---------------  | ------------  |
|SWITZERLAND | Switzerland has a lot to offer, including the magnificent natural beauty of the Alps, serene lakes, charming villages, vibrant cities, and imposing castles. It gets much better when you include some shopping, wine tasting, and delicious cheeses.  | 90 DAYS |
| INDIA |  India, blessed with a wealth of natural beauty, draws millions of tourists from around the world every year with its allure. There are many reasons to travel to India, including the country's mountains, plains, beaches, backwaters, wildlife excursions, adventure activities, isolated islands, thriving cities, gastronomic pleasures, local libations, spiritual holidays, and romantic getaways.   | 180 DAYS  |
| SPAIN |  Spain truly has it all, from breathtaking scenery and beaches to delectable cuisine and a lengthy history, not to mention amazing museums and beautiful architecture. Here are a some of the explanations for why you ought go go at least once in your life.  | 60 DAYS  |
| FRANCE |  The captivating beauty that France possesses cannot be ignored. You've never been to France, yet it has a lot to offer. Without a doubt, it would lead you down memory lane. Images of the Paris Eiffel Tower, the Cannes Film Festival, Nice's pebbly beaches, the best wines of Bordeaux, and the stunning architecture of Lyon invigorate you. Even though half of the globe already adores France, there are countless reasons to fall even more in love with the country.  | 30 DAYS |
| JAPAN |  One of the oldest civilizations, Japan has a stunning and varied past. The gorgeous, diverse landscape, which the Japanese love for its mountains and breathtaking views, offers so many diverse experiences that draw travelers from all over the world.  | 30 DAYS | 

-----
# PITHY QUOTES

> "Behind every great man is a woman rolling her eyes" *― Jim Carrey*

> "The secret of staying young is to live honestly, eat slowly, and lie about your age."*—Lucille Ball*


------
# Code Fencing

> Sass scrollbar style mixin working in textarea but not in random container
 Link to the question :https://stackoverflow.com/questions/74687925/sass-scrollbar-style-mixin-working-in-textarea-but-not-in-random-container

 ```
 @mixin scrollbars($size, $foreground-color, $background-color: mix($foreground-color, white,  50%)) {
  // For Google Chrome
  &::-webkit-scrollbar {
    width:  $size;
    height: $size;
  }

  &::-webkit-scrollbar-thumb {
    background: $foreground-color;
  }

  &::-webkit-scrollbar-track {
    background: $background-color;
  }

  // For Internet Explorer
  & {
    scrollbar-face-color: $foreground-color;
    scrollbar-track-color: $background-color;
  }
}
Usage:
body {
  @include scrollbars(10px, pink, red);
}
.custom-area {
  @include scrollbars(.5em, slategray);
}

Link to the code: https://css-tricks.com/snippets/sass/custom-scrollbars-mixin/
 ```
