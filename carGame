# Car Game
# start - Start the car
# stop - stop the car
# quit - quit the game
# anything else - i don't understand
command2 = "STOP"
command1 = "Na"
while command1 != "QUIT":
    command1 = input("> ").upper()
    if command1 == command2:
        if command1 == "START":
            print("Car has already started.")
        elif command1 == "STOP":
            print("Car has already stop.")
    elif command1 != command2:
        if command1 == "START":
            print("Car has started.")
        elif command1 == "STOP":
            print("Car has stopped.")

    if command1 != "START" and command1 != "STOP" and command1 != "QUIT":
        print("Sorry I didn't understand anything")

    if command1 == "START" or command1 == "STOP":
        command2 = command1
else:
    print("Game has ended")
