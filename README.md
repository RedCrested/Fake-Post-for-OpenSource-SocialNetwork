# Fake Post

Allow the Admin to create and schedule posts. Also, Admin can send fake posts between users.

To generate many fake users as you want, install the [Fake Users component](https://www.opensource-socialnetwork.org/component/view/254/fakeusers). If you create fake users manually, set @example.org as the mail domain or change param.php to the desired mail domain.

It's mandatory to add a cron job on your server in order to process the scheduled posts.

### Features:

* Post with customized text
* Post with image and text
* Posts with image only
* Posts with link
* Posts with link and text
* Each fake post is sent only 1 time into the timeline
* Posts scheduled to be sent in the future date and time
* If the fake post failed to be sent into the wall, the Admin can see, fix and reschedule
* In the param.php file, the admin can:
  * Set the domain name to select the post author fake users. Default value is 'example.org'
  * Set the number of fake posts that will be sent to the newsfeed on each cron run. Default value is 1
  * Allow the fake users to post in real users timeline. Default value is false

 ![](https://www.redcrested.net/components/FakePost/fakepost-1.jpg)

 ![](https://www.redcrested.net/components/FakePost/fakepost-2.png)

## How to buy
I am selling this component for US$30.00 through the Buy me a coffee website. To purchase, visit [https://www.buymeacoffee.com/redcrested/e/139991](https://www.buymeacoffee.com/redcrested/e/139991) or click on button

[![](https://redcrested.net/res/img/button.png)](https://www.buymeacoffee.com/redcrested/e/139991)

## Limitations

The component was tested in free version of OSSN 6.4 and 7.0, in the GoBlue theme. Maybe some adjustments are required in older versions and/or other themes. 

## Version

-1.2.1
    - Fixed an issue in post with image
- 1.2
   - Added support to text with break lines
- 1.1
    - Added new item in param.php to allow or not fake users to post in real users timeline
- 1.0
    - Initial version

    
## Contributing

Send email to [contact@redcrested.net](contact@redcrested.net).

## License

Go to [Red Crested License](http://www.redcrested.net/license) to read the last version of our terms.
