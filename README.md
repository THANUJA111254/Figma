# Ex09 Event Registration Web Application
## Date:

## AIM:
To design, develop and deploy a web application for event registration.

## DESIGN STEPS:

### Step 1:
Create a new frame.

### Step 2:
Select any one preset size of your choice.

### Step 3:
Select the shapes you need.

### Step 4:
Import images as needed.

### Step 5:
Create pages based on your need and link them.

### Step 6:

Validate the HTML and CSS code.

### Step 6:

Publish the website in the given URL.

## DESIGN TOOL:
Figma

## CODE:
  ### HOME PAGE:
  ```
    <style>
  .sports-event-container {
    background-color: rgba(214, 148, 212, 1);
    display: flex;
    max-width: 539px;
    flex-direction: column;
    overflow: hidden;
    color: rgba(0, 0, 0, 1);
    text-align: center;
    font: 400 64px Island Moments, sans-serif;
  }

  .event-wrapper {
    display: flex;
    flex-direction: column;
    position: relative;
    min-height: 864px;
    width: 100%;
    align-items: center;
    padding: 141px 80px 8px;
  }

  .background-image {
    position: absolute;
    inset: 0;
    height: 100%;
    width: 100%;
    object-fit: cover;
    object-position: center;
  }

  .content-container {
    position: relative;
    display: flex;
    width: 258px;
    max-width: 100%;
    flex-direction: column;
  }

  .logo {
    aspect-ratio: 1.24;
    object-fit: contain;
    object-position: center;
    width: 181px;
    align-self: center;
    margin-left: 10px;
    max-width: 100%;
  }

  .event-title {
    z-index: 10;
    background-color: rgba(238, 239, 240, 1);
    margin-top: 41px;
    padding: -5px 33px 50px;
  }

  .actions-container {
    display: flex;
    margin-top: 67px;
    flex-direction: column;
    padding: 0 8px 0 18px;
  }

  .login-button {
    z-index: 10;
    background-color: rgba(224, 230, 235, 1);
    width: 223px;
    max-width: 100%;
    white-space: nowrap;
    padding: -5px 41px 22px;
    cursor: pointer;
    tabindex: 0;
  }

  .register-button {
    z-index: 10;
    background-color: rgba(233, 239, 244, 1);
    align-self: center;
    margin-top: 81px;
    width: 184px;
    max-width: 100%;
    white-space: nowrap;
    padding: -9px 5px 21px;
    cursor: pointer;
    tabindex: 0;
  }

  .tagline {
    font-size: 36px;
    margin-top: 67px;
  }

  @media (max-width: 991px) {
    .sports-event-container {
      font-size: 40px;
    }

    .event-wrapper {
      max-width: 100%;
      font-size: 40px;
      padding: 100px 20px 0;
    }

    .content-container {
      font-size: 40px;
    }

    .event-title {
      font-size: 40px;
      margin-top: 40px;
      padding: 0 20px;
    }

    .actions-container {
      margin-top: 40px;
      font-size: 40px;
    }

    .login-button {
      font-size: 40px;
      margin-left: 9px;
      white-space: initial;
      padding: 0 20px;
    }

    .register-button {
      font-size: 40px;
      margin-top: 40px;
      white-space: initial;
    }

    .tagline {
      margin-top: 40px;
    }
  }

  .visually-hidden {
    position: absolute;
    width: 1px;
    height: 1px;
    padding: 0;
    margin: -1px;
    overflow: hidden;
    clip: rect(0, 0, 0, 0);
    border: 0;
  }
</style>

<div class="sports-event-container">
  <div class="event-wrapper">
    <img
      loading="lazy"
      src="https://cdn.builder.io/api/v1/image/assets/402ad63609fa42ceaae99dbf2ce6be35/d8666036708e2265861e24f0b08b8bba09219ad18968757fd8727a4055c7081e?apiKey=402ad63609fa42ceaae99dbf2ce6be35&"
      class="background-image"
      alt=""
    />
    <div class="content-container">
      <img
        loading="lazy"
        src="https://cdn.builder.io/api/v1/image/assets/402ad63609fa42ceaae99dbf2ce6be35/88f9e60f1d47304d4bda865da140c2bf5c1d7f0b6ec76fabef43fbb50e996e75?apiKey=402ad63609fa42ceaae99dbf2ce6be35&"
        class="logo"
        alt="Sports Event Logo"
      />
      <div class="event-title">
        sports day event
      </div>
      <div class="actions-container">
        <div class="login-button" role="button" tabindex="0">Login</div>
        <div class="register-button" role="button" tabindex="0">Register</div>
        <div class="tagline">
          born to conquer
        </div>
      </div>
    </div>
  </div>
</div>

```
### EVENTS:
```
<style>
  .sports-events-container {
    background-color: rgba(255, 255, 255, 1);
    display: flex;
    max-width: 544px;
    padding-bottom: 17px;
    flex-direction: column;
    overflow: hidden;
  }
  .events-wrapper {
    display: flex;
    flex-direction: column;
    position: relative;
    min-height: 864px;
    width: 100%;
    align-items: start;
    padding: 96px 80px 15px;
  }
  @media (max-width: 991px) {
    .events-wrapper {
      max-width: 100%;
      padding: 0 20px;
    }
  }
  .background-image {
    position: absolute;
    inset: 0;
    height: 100%;
    width: 100%;
    object-fit: cover;
    object-position: center;
  }
  .main-title {
    position: relative;
    color: rgba(0, 0, 0, 1);
    text-align: center;
    margin-left: 10px;
    font: 400 64px Island Moments, sans-serif;
  }
  @media (max-width: 991px) {
    .main-title {
      font-size: 40px;
    }
  }
  
</style>

<div class="sports-events-container">
  <div class="events-wrapper">
    <img
      loading="lazy"
      src="https://cdn.builder.io/api/v1/image/assets/402ad63609fa42ceaae99dbf2ce6be35/9ea67f367bf3c926b97fe8135464674486e61036427b38b1fa5b3288850e6801?apiKey=402ad63609fa42ceaae99dbf2ce6be35&"
      class="background-image"
      alt="Sports day events background"
    />
    <h1 class="main-title">sports day events</h1>
    <div class="cricket-container">
      <img
        loading="lazy"
        src="https://cdn.builder.io/api/v1/image/assets/402ad63609fa42ceaae99dbf2ce6be35/9a52bb25b8fa3adaf4ec4689d9b66f0b241e3eca84e051e256744069c649a3a2?apiKey=402ad63609fa42ceaae99dbf2ce6be35&"
        class="sport-icon"
        alt="Cricket icon"
      />
      <div class="sport-title">cricket</div>
    </div>
    <div class="badminton-container">
      <div class="icon-wrapper">
        <img
          loading="lazy"
          src="https://cdn.builder.io/api/v1/image/assets/402ad63609fa42ceaae99dbf2ce6be35/9a52bb25b8fa3adaf4ec4689d9b66f0b241e3eca84e051e256744069c649a3a2?apiKey=402ad63609fa42ceaae99dbf2ce6be35&"
          class="sport-icon"
          alt="Badminton icon"
        />
      </div>
      <div class="sport-name">badminton</div>
    </div>
    <div class="volleyball-container">
      <img
        loading="lazy"
        src="https://cdn.builder.io/api/v1/image/assets/402ad63609fa42ceaae99dbf2ce6be35/9a52bb25b8fa3adaf4ec4689d9b66f0b241e3eca84e051e256744069c649a3a2?apiKey=402ad63609fa42ceaae99dbf2ce6be35&"
        class="sport-icon"
        alt="Volleyball icon"
      />
      <div class="sport-name">volleyball</div>
    </div>
    <div class="track-event">100 mts</div>
    <img
      loading="lazy"
      src="https://cdn.builder.io/api/v1/image/assets/402ad63609fa42ceaae99dbf2ce6be35/9a52bb25b8fa3adaf4ec4689d9b66f0b241e3eca84e051e256744069c649a3a2?apiKey=402ad63609fa42ceaae99dbf2ce6be35&"
      class="track-icon"
      alt="100 meters track icon"
    />
    <div class="track-event">200 mts</div>
    <img
      loading="lazy"
      src="https://cdn.builder.io/api/v1/image/assets/402ad63609fa42ceaae99dbf2ce6be35/9a52bb25b8fa3adaf4ec4689d9b66f0b241e3eca84e051e256744069c649a3a2?apiKey=402ad63609fa42ceaae99dbf2ce6be35&"
      class="track-icon"
      alt="200 meters track icon"
    />
    <div class="track-event">400 mts</div>
    <img
      loading="lazy"
      src="https://cdn.builder.io/api/v1/image/assets/402ad63609fa42ceaae99dbf2ce6be35/9a52bb25b8fa3adaf4ec4689d9b66f0b241e3eca84e051e256744069c649a3a2?apiKey=402ad63609fa42ceaae99dbf2ce6be35&"
      class="track-icon"
      alt="400 meters track icon"
    />
    <div class="relay-container">
      <img
        loading="lazy"
        src="https://cdn.builder.io/api/v1/image/assets/402ad63609fa42ceaae99dbf2ce6be35/9a52bb25b8fa3adaf4ec4689d9b66f0b241e3eca84e051e256744069c649a3a2?apiKey=402ad63609fa42ceaae99dbf2ce6be35&"
        class="sport-icon"
        alt="Relay race icon"
      />
      <div class="sport-name">4x100 relay</div>
    </div>
  </div>
</div>
```
### REGISTER:

```
<style>
.registration-container {
  background-color: #fff;
  display: flex;
  max-width: 544px;
  flex-direction: column;
  overflow: hidden;
  color: #000;
  text-align: center;
  font: 400 24px Inter, sans-serif;
}

.registration-wrapper {
  display: flex;
  flex-direction: column;
  position: relative;
  min-height: 873px;
  width: 100%;
  align-items: start;
  padding: 32px 74px;
}

.background-image {
  position: absolute;
  inset: 0;
  height: 100%;
  width: 100%;
  object-fit: cover;
  object-position: center;
}

.form-title {
  position: relative;
  align-self: center;
  font: 48px Island Moments, sans-serif;
}

.form-field {
  position: relative;
  background-color: #fff;
  width: 338px;
  max-width: 100%;
  padding: 6px 70px 13px;
}

.form-field-spacing {
  margin-top: 34px;
}

.form-field-gender {
  margin-top: 32px;
}

.form-field-age {
  margin-top: 39px;
  padding: 2px 70px 12px;
}

.form-field-register {
  margin-top: 38px;
  padding: 7px 70px;
}

.form-field-department {
  margin-top: 42px;
  padding: 11px 70px 4px;
}

.form-field-mobile {
  margin-top: 48px;
}

.form-field-email {
  margin-top: 50px;
}

.form-field-events {
  margin-top: 38px;
  padding: 7px 63px;
}

.submit-button {
  position: relative;
  background-color: rgb(104, 221, 26);
  width: 327px;
  max-width: 100%;
  color: #fff;
  margin: 81px 0 0 11px;
  padding: 0 70px 37px;
  font: 48px Island Moments, sans-serif;
  border: none;
  cursor: pointer;
}

.visually-hidden {
  position: absolute;
  width: 1px;
  height: 1px;
  padding: 0;
  margin: -1px;
  overflow: hidden;
  clip: rect(0, 0, 0, 0);
  border: 0;
}

@media (max-width: 991px) {
  .registration-wrapper {
    max-width: 100%;
    padding: 0 20px;
  }
  
  .form-title {
    font-size: 40px;
  }
  
  .form-field {
    padding: 0 20px;
  }
  
  .form-field-department {
    margin-top: 40px;
  }
  
  .form-field-mobile {
    margin-top: 40px;
  }
  
  .form-field-email {
    margin-top: 40px;
  }
  
  .submit-button {
    font-size: 40px;
    margin: 40px 0 0 10px;
    padding: 0 20px;
  }
}
</style>

<div class="registration-container">
  <div class="registration-wrapper">
    <img
      class="background-image"
      src="https://cdn.builder.io/api/v1/image/assets/402ad63609fa42ceaae99dbf2ce6be35/3a6df76154fee0ce491776ba13477212f0aa0050342acdbe773ad5f2165ccde0?apiKey=402ad63609fa42ceaae99dbf2ce6be35&"
      alt=""
      loading="lazy"
    />
    
    <h1 class="form-title">event registration form</h1>
    
    <form>
      <div class="form-field form-field-spacing">
        <label for="fullName" class="visually-hidden">Full name</label>
        <input type="text" id="fullName" name="fullName" placeholder="Full name" required aria-label="Full name">
      </div>

      <div class="form-field form-field-gender">
        <label for="gender" class="visually-hidden">Gender</label>
        <select id="gender" name="gender" required aria-label="Gender">
          <option value="">Select Gender</option>
          <option value="male">Male</option>
          <option value="female">Female</option>
          <option value="other">Other</option>
        </select>
      </div>

      <div class="form-field form-field-age">
        <label for="age" class="visually-hidden">Age</label>
        <input type="number" id="age" name="age" placeholder="Age" required aria-label="Age">
      </div>

      <div class="form-field form-field-register">
        <label for="registerNumber" class="visually-hidden">Register number</label>
        <input type="text" id="registerNumber" name="registerNumber" placeholder="Register number" required aria-label="Register number">
      </div>

      <div class="form-field form-field-department">
        <label for="department" class="visually-hidden">Department</label>
        <input type="text" id="department" name="department" placeholder="Department" required aria-label="Department">
      </div>

      <div class="form-field form-field-mobile">
        <label for="mobileNumber" class="visually-hidden">Mobile Number</label>
        <input type="tel" id="mobileNumber" name="mobileNumber" placeholder="Mobile Number" required aria-label="Mobile Number">
      </div>

      <div class="form-field form-field-email">
        <label for="email" class="visually-hidden">Email</label>
        <input type="email" id="email" name="email" placeholder="Email" required aria-label="Email">
      </div>

      <div class="form-field form-field-events">
        <label for="events" class="visually-hidden">Events to register</label>
        <select id="events" name="events" required aria-label="Events to register">
          <option value="">Select Events</option>
          <option value="event1">Event 1</option>
          <option value="event2">Event 2</option>
          <option value="event3">Event 3</option>
        </select>
      </div>

      <button type="submit" class="submit-button">register</button>
    </form>
  </div>
</div>

```
###  THANK YOU:
~~~
<style>
.thank-you-container {
  background-color: rgba(255, 255, 255, 1);
  display: flex;
  max-width: 544px;
  flex-direction: column;
  overflow: hidden;
  color: rgba(0, 0, 0, 1);
  text-align: center;
  font: 400 48px Island Moments, sans-serif;
}

.content-wrapper {
  display: flex;
  flex-direction: column;
  position: relative;
  min-height: 873px;
  width: 100%;
  padding: 12px 61px 350px;
}

.background-image {
  position: absolute;
  inset: 0;
  height: 100%;
  width: 100%;
  object-fit: cover;
  object-position: center;
}

.logo-image {
  aspect-ratio: 4.55;
  object-fit: contain;
  object-position: center;
  width: 422px;
}

.thank-you-message {
  position: relative;
  align-self: start;
  margin: 116px 0 -70px;
}

.visually-hidden {
  position: absolute;
  width: 1px;
  height: 1px;
  padding: 0;
  margin: -1px;
  overflow: hidden;
  clip: rect(0, 0, 0, 0);
  border: 0;
}

@media (max-width: 991px) {
  .thank-you-container {
    font-size: 40px;
  }
  
  .content-wrapper {
    max-width: 100%;
    font-size: 40px;
    padding: 0 20px 100px;
  }
  
  .logo-image {
    max-width: 100%;
  }
  
  .thank-you-message {
    font-size: 40px;
    margin: 40px 0 10px;
  }
}
</style>

<div class="thank-you-container">
  <div class="content-wrapper">
    <img
      loading="lazy"
      src="https://cdn.builder.io/api/v1/image/assets/402ad63609fa42ceaae99dbf2ce6be35/d841cdf434d3b39c937dae608da126cf7d4a0d9f6386b205a65861b9ce40b22d?apiKey=402ad63609fa42ceaae99dbf2ce6be35&"
      class="background-image"
      alt=""
    />
    <img
      loading="lazy"
      src="https://cdn.builder.io/api/v1/image/assets/402ad63609fa42ceaae99dbf2ce6be35/2cf0686900cf012c368af2435f612ad3713341fc357a97733a1006c88ab6b7ab?apiKey=402ad63609fa42ceaae99dbf2ce6be35&"
      class="logo-image"
      alt="Company Logo"
    />
    <div class="thank-you-message">
      Thank you
      <br />
      <br />
      <br />
      we are eagerly waiting for your participation in the sports events
      <br />
      <br />
    </div>
  </div>
</div>

~~~
## OUTPUT:
![image](https://github.com/user-attachments/assets/5dfeb706-bd1f-4a5f-a921-5e4016c02058)


## RESULT:
The program to design, develop and deploy a web application for event registration is completed successfully.
