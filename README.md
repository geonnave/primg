# primg

Inspired by this: [Does there exist a prime number whose representation on a phone screen looks like a giraffe?](https://www.reddit.com/r/math/comments/7qpfls/does_there_exist_a_prime_number_whose/?st=jcwjmz50&sh=1dfbb1b2)

![screenshot](screenshot1.png "Screenshot")

Access it here https://geonnave.github.io/primg/.

# ToDo

- [x] ~~find a way to update the DOM while doing heavy processing~~ solved: Web Workers to the rescue
- [x] ~~use a more clever way (maybe histograms stuff) to find the threshold number~~ now using average of image
- [x] ~~make it faster (currently takes minutes)~~ "solved" by reducing canvas size from 50x50 to 32x32
- [ ] make it prettier
- [ ] make code cleaner
