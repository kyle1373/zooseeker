# zooseeker
This is an Android mobile application which allows the user to search for an animal in the San Diego Zoo database and adds it to a route plan. The user is then able to start a route based on the animals they have chosen, in which the app generates an efficient route using a greedy dijsktra's algorithm on all selected nodes.

# Demo
![image](https://user-images.githubusercontent.com/59634395/178122225-6dd3c077-1bce-43bf-93e9-38962d263540.png)
When the user opens the app, it should take it to this screen. Then, the user can type anything in the search bar to find an animal in the database.
![image](https://user-images.githubusercontent.com/59634395/178122254-a48abccd-fbfb-4942-b540-0b8eb1deabf6.png)
Then, the user can add any animal through clicking the associates "ADD" button. The user can then go to the plan tab to find the animals that they have selected.
![image](https://user-images.githubusercontent.com/59634395/178122303-66a35123-9669-4001-99e0-a67c1a111158.png)
The user can either clear the plan or start a route. If the user starts the route, it will take the user to the route summary page.
![image](https://user-images.githubusercontent.com/59634395/178122325-96097d77-2a3a-4daa-9c03-2d7535893eca.png)
Here, it shows a route summary based on distances between each step.
![image](https://user-images.githubusercontent.com/59634395/178122342-09d9c8da-30c5-4806-a14d-dfee13bea5af.png)
Now, the user can start the route through stepping through the plan. The user can go to the next step through clicking "Next" or can go to the previous step by clicking "Back." If the user wants to skip the exhibit they want to go to, they can click "Skip" and go to the next exhibit. If the user wants to swap the current exhibits and get the reversed directions, they can click reverse. If the user wants to toggle between brief directions or detailed directions to the next exhibit (brief directions combines the distances that they have to travel if they are going on the same road while detailed directions splits up the road to different stops along the way), they can toggle between brief directions and detailed directions. If the user wants to delete the entire route plan, they can click delete all, and if the user wants to reroute to the closest exhibit to them based on their real GPS location, they can click reroute. The user is also able to mock their GPS location by clicking on the menu at the top and inputting GPS coordinates. The following is a demo based on these actions.
TO BE FILLED OUT LATER
