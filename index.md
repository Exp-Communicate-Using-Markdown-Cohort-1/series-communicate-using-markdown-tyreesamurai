# This is clearly an H1.

### While this is an H3.

## I think that this H2 might like H3 more than H1.

#### Why? Asks H4.

##### H5 says, "Because H1 ate H6!"

###### H6: x.x

![funny image about internet explorer being slow](https://atlascorps.org/wp-content/uploads/2013/08/funny-internet-browsers.jpg)


```
{
    init: function(elevators, floors) {
        var elevator = elevators[0]; // Let's use the first elevator

        // Whenever the elevator is idle (has no more queued destinations) ...
        elevator.on("idle", function() {
            // let's go to all the floors (or did we forget one?)
            elevator.goToFloor(0);
            elevator.goToFloor(1);
        });
    },
}
```


- [x] Make Headers
- [x] Add Image
- [x] Add Code
- [x] Make List
- [ ] Merge Pull Request
