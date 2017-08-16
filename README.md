# browser-test

* This repostory contains a selenium browser test for Walmart.com home page title information.

* To build the image, run: `docker build -t selenium/standalone-chrome .`
* To run the image, run: `docker run -d -p 4444:4444 selenium/standalone-chrome`
* Finally, to run the test, run: `bundle exec ruby browser_test.rb`

If the test succeeds, it will create a screenshot file called: `selium-docker-Walmart-home-page.png`
