# Tutorial Display Temperature in Celsius on the LED Screen

## Step 1 
In "Basic", scroll down, click and drag the ``||basic.forever||`` block onto your code workspace. 


```blocks
basic.forever(function () {
```

## Step 2
Go back to "Basic" scroll down, click and drag the ``||basic.show_number||`` code and drop it into the ``||basic.forever||`` block.
Go to "Input"scroll down, select, and drag ``||input:temperature||`` into the variable "O" on the ``||basic.show number||`` code line. 

```blocks
    basic.showNumber(input.temperature())

```

## Step 3
Go back to "Basic", scroll down to ``||basic.pause(ms)||``, and drag and drop it as the last line of code in the ``||basic.forever||`` block.
On the ``||basic.pause(ms)||``, double click the white numberical field and change the value to 2000.

```blocks
    basic.showNumber(input.temperature())
    basic.pause(2000)
})

```

## Step 4
You are now ready to see the temperature scroll accross your LED screen.  Congratulations, you did it!

    