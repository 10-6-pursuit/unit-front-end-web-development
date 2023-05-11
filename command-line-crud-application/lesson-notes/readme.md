# Command-line CRUD Application

Build a VIP app. This app should allow a user to:

- Add a new name to a guest list
  - each guest should have
    - `id` - unique, generated by `nanoid`.
    - `name`- a string
    - `vip`- a boolean whether the person is VIP. By default, everyone's VIP status is false
- Show a list of names on the guest list
- Delete a name from the guest list
- Update a name to have VIP status (vip: true)
- Show the total number of people who are VIP

## Lesson Objectives

By the end of this lesson

- Develop a list of minimal features
- Create an app that uses user input to
- Create data
- Read data
- Delete data
- Update data

## Guiding Questions

- What are the minimum features for this app?
- Can you define these features using the "A user can..." pattern?

- What are the scripts you need to write?
- How can you control which action is taken in your `run` function
- Should you use an if/else statement or a `switch` statement? Or still a different approach?

- Since you are using the command line, sometimes you might want to use `console.log()` for your own development, but sometimes you might want to use it to inform the user. How can you distinguish the two use cases in your code?

- To save the data to a file, which npm package or built-in module would you use?

- What happens if your guest list has four people named `Cameron` on it? How can you be sure you update/delete the correct one?
- What package can you use to generate a unique id for your project?
- Faker.js also had similar functionality. What is the reasoning for NOT installing Faker.js instead?
- Why is using ids necessary?

- How can you set a default value of `vip: false` for each new guest?

- When you run `npm run index`, you want the people with `vip:true` to have their names logged in a different color. What npm package could you use?
- What logic would you need to write to complete this feature?

- How can you delete someone from the guest list?
- Is it essential to inform the user that this action happened successfully?

- How can you update someone from the guest list?

- Write the functionality so that when someone runs `npm run vip` - it shows

```
x out of y people are VIPs for this event.
```

    Where x is the number of VIPs and y is the total number of people.