# primg

Inspired by this: [Does there exist a prime number whose representation on a phone screen looks like a giraffe?](https://www.reddit.com/r/math/comments/7qpfls/does_there_exist_a_prime_number_whose/?st=jcwjmz50&sh=1dfbb1b2)

![screenshot](screenshot.png "Screenshot")

Access it here https://geonnave.github.io/primg/.

**Note**
- It may take MINUTES to find a prime number
- Due to a naive method for choosing the threshold (fixed at 128), not all images will have good results. Here is an example of one that will look good: [click here](https://i.ytimg.com/vi/mjUvJnjhlhY/maxresdefault.jpg)

# ToDo

- [x] find a way to update the DOM while doing heavy processing
- [x] use a more clever way (maybe histograms stuff) to find the threshold number (now using average of image)
- [ ] make it faster (currently takes minutes)
- [ ] make it prettier
- [ ] make code cleaner
