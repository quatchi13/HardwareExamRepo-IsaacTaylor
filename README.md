# HardwareExamRepo-IsaacTaylor
Repo for file uploads of Hardware Practical Component

The Design:

I came up with the idea to look simaller to a basic duck shape, focusing on th ebody and head of the duck. more resemblance would be added through colors that match to one of the ducks within the game. There are three buttons for this controller. that all effect movement in some way, the two primary ones on the left allow users to switch between moving up and down, and the right one allows the user to toggle the direction the are moving, left or right. When using this button to switch horizontal direction a very brief "speed boost" will jump the duck forwards to help get them out of that spot. This button does have a cooldown of a few seconds bfore being activatable again. I kept this more binary movement because in the original game the ducks start somewhere and then must bounce around the screen, never changing their path from direct bounces. In this controller the controllable duck wll always be moving at a given speed and the player is able to control the movement directions of the duck freely rather than needing to hit a wall, allowing for more creative dodging and a harder to predict target. The "eye" of the duck is an LED (primitive used in CAD) that will light up whenever one of the buttons has been pressed and has actually performed the action. For example pushing up when moving down will trigger the light but pushing up while already moving up will not. 

I started with the idea of creating some thing duck like, with the designs of decoy ducks in mind, simple to identify and able to be enhanced visually through visuals applied to their surface later in production. I then began to decide on the functionallity and decided keeping the ducks options limited would be the best way to ensure that both the player and hunter wouldbe able to still have a fair chance (this design would be used adjacent to the existing NES Zapper so another human player would still be the hunter). After deciding on their functions as described above, I moved into Fusion to begin the CAD mockup of the controller. I wanted to keep the controller very simple with only two parts, a base for the components to rest on and a cover to enclose them. so I created the duck silohuette i wanted then placed the components inside, split the body along the underside of the components, shelled the top half and had the simple controller design. I then developed the technical drawings of the two components and created the assembly drawing. I then created the TinkerCad rendition of thecircuity to showcase functionality of the controllers electronics.

As the project is developed in an exam scenario obviously no outside input was recived in the development idea so it is almost guarenteed that some part of this design is inheritly flawed or missing. Fisrt steps for improovement would be to bring in others on the basic idea. Do the button layouts make sence? do their functions seem practical and enjoyable to use while playing? Is the controller to large, or too small for users to hold easily? these questions and more would need to get asked even before generating an actual physical prototype of anything. After consulting with others the project can use that feedback to improove on the design and ensure it is usable and actually satisfies the need as intended.


Components Explination:

The components are incredibly simple to keep the time of creation down, there are only two of them. The first component is the controller cover this piece is to enclose the electronics and has the visual of the duck printed onto it, it has no further purpose but to increase the controllers reesemblance to the ducks in game and ensure that the components are not exposed while utilizing the controller.

The second component is the controllers base, the component is the core of the design and houses all of the electronic components on top of it. The controller base is solid to grant the controller more sctructural stability and to give the controller a bit more weight to not feel fragile.


Assembly Explination:

These two components are connected via a hinge in the center of the ducks back (the top/flat side of the controller) to allow for easy acsess to internal components if required. This being the largest flat section it makes the most sence to allow the duck to open from this spot as the hinge will be easier to create opposed to attempting to place one along one of the curved edges. The pieces are naturally have the base first and the cover attached after wards so that the controller can be put together in full and tested for functionality of the electronics and then the cover can be added after all tests have concluded since the covers purpose is purly aethstetic.


Electronics Explination:

I made the electronics to reprisent a simple version of the idea presented by the controller, thee different buttons that will all activate the same LED when pressed. The exact functionalities of the light only lighting when an action is performed is not accounetd for here, (no tracking which way the duck is moving or if the button is off cooldown). This simple simulation shows how the controller behaves while used outside of game logic, focusing only on the positive cases to showcase tat this wiring would allow each button to light the LED and further conditions can be applied through code later to enable things like the cooldown.


Link to TinkerCad: https://www.tinkercad.com/things/egznTOQTEwM-brilliant-hango-lahdi/editel?sharecode=gNHMVQ2oouvGuhtcsxjrlE-7wJzsqzlYGRfeCNjwbLI




















