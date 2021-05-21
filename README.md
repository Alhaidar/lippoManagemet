##  Supply chain managemet, untuk persewaan ruko di Plaza.

## **Technology: Html, CSS, Bootstrap, JavaScript, PHP, Laravel Framework
## **Database: MySQL

<ul>
<h2> Fitur yang tersedia saat ini </h2>
<h2>Core Features:</h2>
    <li><b>Multiauth role (Admin/ Landlord(Petugas Penyewa)/ Penyewa (Renter))</b></li>
    <li><b>Booking System</b> (Ruko booking)</li>
    <li>Google Login using Socialite Package</li>
    <li><b>SMS</b> System (When booking is confirmed by admin then confirmation sms sends to renter)</li>
    <li>Social media sharing (available ruko)</li>
    <li>Price Filter (cari harga ruko menggunakan  price range)</li>
    <li>Admin, Landlord, Renter Panel </li>
    <li><b>Email Verification</b>, Forget Password, Reset Passwrod</li>
    <li>Landlord and Renter are supervised by admin</li>
    <li>Booking history</li>
    <li>Cancel Booking Request</li>
    <li>Awesome overview show in <b>Dashboard</b></li>
    <li>Searching System (search by rooms, toilet, rent, area.)</li>
    <li>Category wise data handling</li>
    <li><b>Login/Register</b></li>
    <li>Update profile information</li>
</ul>


##  Activities
<ul>
<h2>For Admin:</h2>
<li>See all areas and ability to add new area and edit/delete them</li>
<li>See all areas created by landlords and ability to delete them.</li>
<li>Manage all landlords & renter.</li>
<li> See all the houses information and ability to delete them</li>
<li>See all booked houses, booking history.</li>
<li>Admin can change his profile information & reset password</li>
<li>Admin can share house details through social media</li>
<li>Sign in/sign out.</li>
</ul>



<ul>
<h2>Landlord Panel</h2>
<li>Sign in/ sign out.</li>
<li>Landlord can create, edit, delete <b>Area</b> (own created)</li>
<li>Landlord can view all areas.</li>
<li>Landlord can add, edit, delete his owm created <b>ruko</b>. </li>
<li>Landlord can see his own created houses information.</li>
<li>Landlord can handle the status of his houses (available or not available)</li>
<li>Landlord can change his profile information</li>
<li>Have option to reset his password</li>
<li>Landlords has ability to approve and reject his pending booking requests.</li>
<li>Landlord can share place/ruko details through social media</li>
<li>Landlord can manage the status of his booked place when renter leaves</li>
<li>Have a nice dashboard where he sees the summary of his activity</li>
</ul>


<ul>
<h2>Renter User</h2>
<li>Sign in/sign out. </li>
<li>Renter can view all areas.</li>
<li>Renter can view all places information</li>
<li>Renter can change his profile information.</li>
<li>Renter can apply booking for rent a place.</li>
<li>Renter can see his own booking history</li>
<li>Renter can see his own pending booking requests. </li>
<li>Renter has ability to cancel his booking request</li>
<li>Renter can get the booking approval/rejection sms in their cell phones</li>
<li>Renter can share place details through social media.</li>
<li>Has ability to reset password</li>
</ul>




<ul>
<h2>Guest User</h2>
<li>User can see all available places</li>
<li>User can search houses by location, number of rooms, bathrooms, rent amount, price range</li>
<li>User can view houses by sorting prices as high to low Or low to high price.</li>
<li>User can view area wise places.</li>
<li>User can share house details through social media.</li>
</ul>

<h2> Cara Instalasi </h2>
clone atau download repo, lalu install semua dependency required sama laravel.

```shell
# install composer-dependency
$ composer install
# install npm package
$ npm install
# build dev
$ npm run dev
```
Sebelum mulai pastikan sudah generate key dan konfigurasi file env serta migrasi aja.

```shell
# create copy of .env
$ cp .env.example .env
# create laravel key
$ php artisan key:generate
# laravel migrate
$ php artisan migrate
```
Untuk dapet akun admin, cukup daftar aja sbg lanlord/renter tapi kalau udah masuk di sql role nya dirubah ke 1

mungkin ada error sama verifikasi email, saya masih blm bisa benerin, akalin aja habis register data sudah masuk
kok ke sql nah verifikasi diisi lewat sana aja.

cheers, noob programmer :")
