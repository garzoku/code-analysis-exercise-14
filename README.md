# Programming Exercise

Your task is to figure out how this code works.

* Come with a test input for the function.
* Trace the flow of the program with your test input **without running the code**, keeping track of all of the variables and transformations until you can determine the output.
* Keep coming up with new inputs until you're confident until you're confident that you know how the function works.
* Write a summary of what the function does.

```js
function (user){
  if (user.isActive){
    return `Welcome back, ${user.username}!`
  } else {
    return `Hey ${user.username}! Would you like to renew your subscription?`
  }
}
```

| Input                                                 | Output                                                            |
| ----------------------------------------------------- | ----------------------------------------------------------------- |
| `Kurt = { isActive: false, username: 'CreepyKurt'}`   | `"Hey CreepyKurt! Would you like to renew your subscription?"`    |           
| `Kyle = { isActive: false, username: 'KnifeBladeKyle'}`| `"Hey KnifeBladeKyle! Would you like to renew your subscription?"`|        
| `Jeb = { isActive: true, username: 'ActiveJeb' }`     | `"Welcome back, ActiveJeb!"`                                       |            

<table>
  <tr>
    <th>What does this program do?</th>
    <td>1). The function parameter accepts an object.<br>
2). If the user object has the value of isActive set to true, then the message in the following block is returned.<br>
3). Else, if the user does not have the .isActive value set to true, a different a message is returned.<br>
Summary: This program checks to see if a user has an active account. If they do, they are greeted by their username. If not, they are asked to renew their subscription.
</td>
  </tr>
</table>

## Rubric

* Contains a plausible collection of test cases
* Outputs are accurately derived from inputs
* Summary is plausible
