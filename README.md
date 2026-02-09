 Movie Ticket Booking System (Django) - Internship Project

This repository contains the final submission for the Nullclass  Internship. The project is an end-to-end movie ticket booking platform integrated with advanced features like real-time seat reservation, payment gateways, and admin analytics.
 Completed Tasks:-

 I have successfully implemented the following features:

1.  Genre & Language Filters: Users can now filter the movie list based on specific genres (e.g., Action, Comedy) and languages (Hindi, English).
2.  Ticket Email Confirmation: Automated email trigger upon successful booking using Django's SMTP backend.
3.  YouTube Trailer Integration: Embedded trailers on movie detail pages to provide a richer user experience.
4.  Payment Gateway Integration: Integrated **Razorpay** with success/failure handling for secure transactions.
5.  Seat Reservation Timeout:** Implemented a **5-minute locking mechanism**. Seats are temporarily reserved during payment and automatically released if the transaction isn't completed.
6.  Admin Dashboard & Analytics:** A custom admin panel showing:
    * Total Revenue 💰
    * Most Popular Movies 🎬
    * Busiest Theaters 🏛️

 Tech Stack

* Backend:Python 3.x, Django 5.x
* Database: SQLite3
* Frontend: HTML5, CSS3 (Arial font styling), Bootstrap
* APIs: Razorpay, YouTube Embed API
