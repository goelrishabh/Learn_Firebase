# FIREBASE

- when you can write a backend of your own?
- Firebase works similar to hosting, so to speak. You pick what services you like, connect them to your application and bam
- It provides a JSON like database in which you store and read data. It  **doesn’t** really follow the REST standard as it has **no REST methods** (GET,  POST…). Here, you’re working directly with the database.

**Firebase** provides a wide array of features that greatly simplify app and web development. Some of these features include:

- **Firebase authentication**: provides backend services, easy-to-use SDKs, and ready-made UI libraries to authenticate users to our apps.
- **Firebase realtime database**: cross-platform cloud-hosted database. Data is stored as JSON and synchronized in realtime to every connected client.
- **Cloud messaging**: cross-platform messaging solution that lets you reliably deliver messages at no cost.
- **Analytics**: free app measurement solution that provides insight on app usage and user engagement.
- **Storage**: powerful, simple, and cost-effective object storage service built for Google scale.
- **Crashlytics**: realtime crash reporter that helps you track, prioritize, and fix stability issues that erode our app quality.

## Rest

- It’s a concept where you use a certain set of methods (GET, POST, DELETE…) to send data, receive data or both.

- And REST is great, but sometimes you just can’t find a (back)end to all  the challenges! More often than not, the variable names are in a  different style than you prefer or the paths to the requests are  confusing…



# Behind the Scenes aka FIREBASE 

https://www.youtube.com/watch?v=gjVg-_oFsEs

### The Essentials:

https://firebase.googleblog.com/2016/09/become-a-firebase-taskmaster-part-1.html

> When we say some work must be done *asynchronously* in an app, that means the work needs to happen at the same time as the app performs its primary job of rendering the app’s views, but not get in the way of that work;  **work can't occupy time on the Android main thread**

