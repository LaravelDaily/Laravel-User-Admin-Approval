# Laravel User Approval by Administrator

Simple demo-project to add administrator's approval on every new user registered.
The core of this project was generated with [QuickAdminPanel](https://quickadminpanel.com) and its [Registration module](https://www.youtube.com/watch?v=gIeVzYl2uJE), manually adding email notifications on top.

Here's a live-coding YouTube video where I explain how it all actually works: [coming soon]

![Laravel user administrator approval login](https://laraveldaily.com/wp-content/uploads/2019/10/Screen-Shot-2019-10-14-at-11.49.36-AM.png)

![Laravel user administrator approval form](https://laraveldaily.com/wp-content/uploads/2019/10/Screen-Shot-2019-10-14-at-11.49.58-AM.png)

---

## How to use

- Clone the repository with __git clone__
- Copy __.env.example__ file to __.env__ and edit database credentials there, also email provider settings (to send verification codes)
- Run __composer install__
- Run __php artisan key:generate__
- Run __php artisan migrate --seed__ (it has some seeded data for your testing)
- That's it: launch the main URL. 
- You can login to adminpanel with default credentials __admin@admin.com__ - __password__

## License

Basically, feel free to use and re-use any way you want.

---

## More from our LaravelDaily Team

- Check out our adminpanel generator [QuickAdminPanel](https://quickadminpanel.com)
- Read our [Blog with Laravel Tutorials](https://laraveldaily.com)
- FREE E-book: [50 Laravel Quick Tips (and counting)](https://laraveldaily.com/free-e-book-40-laravel-quick-tips-and-counting/)
- Subscribe to our [YouTube channel Laravel Business](https://www.youtube.com/channel/UCTuplgOBi6tJIlesIboymGA)
- Enroll in our [Laravel Online Courses](https://laraveldaily.teachable.com/)
