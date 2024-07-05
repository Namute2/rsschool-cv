# rsschool-cv

# Georgiev Nikita
## Contacts

* Location: Minsk, Belarus
* Phone: +375 29 652-92-01
* Email: georgievnikita34@gmail.com
* Github: [Namute2](https://github.com/Namute2)

## About me
Bsuir student at Junior-level(*third-year student*), an excellent team worker and striving to learn and develop new skills.
Intersted in Web-development because it follows my passion with design and programming.

## Skills

*C/C++
*Java
*3D-modeling
*Git

## Code example
```
  public Activity getActivityById(Long id) {
    Activity activity = cache.get(id);
    if (activity == null) {
      activity = activityRepository.findById(id).orElse(null);
      if (activity != null) {
        cache.put(id, activity);
      }
    }
    return activity;
  }
```