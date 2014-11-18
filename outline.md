#Blink(1)ing your way to USB

###Why

* Fun
* Small utilities
* Measuring
* Examining peripherals for IoT
	* Gallileo
* Do we really need to create IoT

###But how does it all work?

* Events
	* In your dreams
	* Here we fake events
* Implementations
	* Quite herpy-derpy
	* Based on horrible APIs
	* Not getting any better

###Get running

* Connecting
	* Frameworks
		* Fantastic to get up and running
		* Prototyping
		* HIDLibrary
			* Will cost you ~35kB
		* MightyHID
		* HIDSharp
		* Etc.
	* Native
		* No tax of an external DLL
		* Hard to write to be honest
			* pInvoke
			* 32/64 bit issues
			* **UNLIMITED POWAH**!!!
		* http://msdn.microsoft.com/en-us/library/windows/hardware/ff538731%28v=vs.85%29.aspx
		* http://msdn.microsoft.com/library/windows/apps/dn278466
* Finding your device
* Read/Write
* Events

##Basic is settled now what?

###Blink(1)

* _Price:_ 
* Simple instructions
	* Sorta well defined structure
	* Very forgiving
* Commands
* Queries
* Creating a better API
	* Not resembling hardware
	* Not resembling the vendor DLL
* Something is not in the box...
	* Version
	* Gamma

###Blink(1) mk2

* _Price:_ 
* Simple evolution
* Has documentation now

###Big Red Button

* _Price:_ 
* Has documentation
* Mission control feeling
	* Lid
	* Button
* When documentation isn't a joy
	* Off by 1
	* Checking for hex values instead of actual bits
	* Not really present for you
* Simple bit operations
* Event driven

###Dragonrise Gamepad

* _Price:_ 
* A bit awkward API, but bearable
* Reversed by inspection and googling

###TEMPer2
* _Price:_ 
* Replacement of 80-90's UI
* No documentation
* Semi-hard to find solutions that give you proper hints
* Most fallback to using COM
* When engineers are on the loose
	* Last resort
* Optimizations
	* For what reason

###Other
* picoLCD
	* _Price:_ 
* Missile launcher
	* _Price:_ 
* ...

##Where do we go next?

* Masocistic approach
	* Spending several hours on figuring out patterns
* Building a new framework
* Supporting the new .NET world
	* *nix
	* OS X
* Fingers crossed for real support
	* Sadly that won't happen
