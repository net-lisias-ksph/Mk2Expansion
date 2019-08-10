# Mk2Expansion :: Change Log

* 2018-0404: 1.0 (SuicidalInsanity) for KSP 1.4.
	+ Craft featured in the Mk2 Expansion banner image in the M2X thread's opening post.
* 2018-0314: 1.8.1 (SuicidalInsanity) for KSP 1.4.
	+ KSP 1.4.X update
		- Part Refactor: L/T/X Hubs lighter, now hold fuel
		- Jets now have custom sounds
		- Fixes LiftFan SurfaceFX
		- Xenon tank mass rebalances
		- Service tank now properly holds 200 Monopropellant
		- update to Russian localization, credit to yalov
* 2018-0120: 1.8.06 (SuicidalInsanity) for KSP 1.3.1
	+ improves throttle response of prop engines
	+ Fixes Turboprop IntakeAir use
	+ Fixes some localization typos
	+ Fixes Siddley VTOL model
* 2017-1101: 1.8.05 (SuicidalInsanity) for KSP 1.3.1
	+ Adds Russian Localization courtesy of yalov
* 2017-1013: 1.8.04 (SuicidalInsanity) for KSP 1.3.1
	+ KSP 1.3.1 update
		- Extends atmCurves for all airbreathing engines; now correctly have higher thrust in denser atmospheres - Eve/Tellumo/etc.
		- Model Rework: Afterburn
		- Model Rework: Mule
		- Model Rework: Vector
		- Model Rework: Omni RCS/OMS blister
		- Fixes Banshee Fan SFX
* 2017-0908: 1.8 (SuicidalInsanity) for KSP 1.3
	+ Fixes Localization issue for Rontgen and Hyperblast
	+ Fixes Sledgehammer AARE not loading
	+ Fixes HS-X cockpit mesh errors
	+ Fixes persistent plume on ESTOC/MATTOCK
	+ Fixes M2X Stork example craft
	+ Fixes Sledgehammer AARE not loading
	+ Adds Localization framework
	+ Adds RealPlume-Stock compatibility
	+ Fixes NFE compatibility patch again
	+ Fixes mesh hole in HS-X Cockpit IVA
	+ Fixes Hypersonic cockpit hatch window emissive
	+ Fixes Shrouded Radiator hatch size
	+ Fixes Decoupler node alignment
	+ Fixes Spatular HSNC emissive
	+ Nerfed Mule Turbofan max thrust slightly
	+ Increased J.Edgar mass to 2.5t
	+ Fixed Banshee Velcurve
	+ Fixed G-120 Turbojet velcurve, now tapers off at high mach
	+ Fixed ESTOC velcurve, now tapers off at high mach
	+ Model Rework: CB-C cockpit
	+ Model Rework: Service Bay
	+ Model Rework: Ion Engine
	+ Model Rework: Adapter Intake
	+ Model Rework: Manta Intake
	+ Model Rework: Engine Shroud
	+ Model Rework: Aerospace Mount
	+ Model Rework: Banshee Fans
	+ Texture Rework: Airlock Endcap
	+ Texture Rework: Reactor
	+ Fixes texture edges on various parts, seams now align properly with stock Mk2 parts
	+ Adds Thermal Emissive to Precooler
	+ Adds Thermal emissive to Circular Intake
	+ Adds Thermal emissive/Engine FX to J.Edgar
	+ Servicebay Xenon/Monoprop tank amounts increased slightly
	+ Service Tank Monoprop tankage increased
	+ Service bay now has togglable interior attach nodes
	+ All crew holding parts now have secondary airlocks at bulkhead doors
	+ All cockpits now have flags
	+ Fixes Specular maps on all parts
* 2017-0715: 1.7.7 (SuicidalInsanity) for KSP 1.3
	+ Updates/fixes NFE patch
	+ Added ConfigurableContainers exception to IFS patch in case of edge case incompatibility
	+ New Part: Long crew tank
	+ New Part: Hollow Structural Adapter Short
	+ New Part: Hollow Structural Adapter Long
	+ Part Rework: Banshee fans now easier to tell which side is up
	+ added surface attach to the mk2 structural tube
	+ reduced Hypersonic Nose fuel capacity
	+ fixes mk2 decoupler drag issue
	+ fixes mesh normal error on Hollow Structural Adapters
	+ Fixes Long Cabin IVA collider issue
* 2017-0530: 1.7.5 (SuicidalInsanity) for KSP 1.3
	+ Update for KSP 1.3
	+ Model Rework: Mk2 Science Lab
	+ Model Rework: SC-TD Multipurpose Cockpit
	+ Model Rework: HSNC now has spatular variant
	+ Model Rework: Nosecap
	+ Model Rework: Rontgen nuclear jet
	+ Model Rework: Linear Aerospike
	+ Banshee Lift Fan SFX volume reduced
	+ HSNC and SSNC now use updated RSCFX
	+ Fixes Omni RCS parts clipping into surfaces
	+ Adds optional MM patch to add reactor heat/decay mechanics to Rontgen
	+ Removes Scramjet thrust Offset
	+ Added Engine Lights
	+ R-71 cockpit now has ASET IVA
	+ Tweakscale Patch has been updated courtesy of eberkain
* 2017-0225: 1.7.35 (SuicidalInsanity) for KSP 1.2
	+ Fixes Vector turbojet attach node
	+ fixes shrouded solar panel MaxTemp
	+ Fixes NUK-3 reactor cooling issue
	+ Max level engineers no longer required for full reactor output, engineers will provide slight boost to reactor output
	+ Added USI compatibility MM patches courtesy of Merkov
	+ Fixes MM patch conflict with GTindustries
	+ Fixes NFE issue with the Pluto NTR
	+ New Part: Mk2 Structural tube
	+ New custom DragCubes for a few parts, should fix drag issues
	+ Model Rework: R-71 cockpit, adds second seat, new IVA
* 2016-1226: 1.7.26 (SuicidalInsanity) for KSP 1.2
	+ New Part: Shrouded Thermal Control System
	+ Part Rework: Hypersonic Nosecone
	+ Part Rework: Spadetail
	+ Hypersonic Cockpit and Hypersonic nosecone max temp increased
	+ Fixed engine FX, removes Aero FX/Engine FX interaction
	+ Tweaked Afterburn thrust curve
	+ 'Vector' turbojet mass reduced
	+ 'Wedge' Linear Aerospike mass reduced
	+ 'Sledgehammer' Air-Augmented rocket thrust reduced
	+ Various part costs adjusted to be more in line with stock prices
* 2016-1113: 1.7.25 (SuicidalInsanity) for KSP 1.2
	+ Fixes Service Bay occulsion issue
	+ Tweaked Ramjet ThrustCurve
	+ Tweaked Scramjet ThrustCurve
	+ Mule Turbofan moved to SupersonicFlight
	+ Scramjet moved to AerospaceTech, costs adjusted
	+ Increased Service Tank resource storage capacity
	+ FF5Way RCS now has Hullmetal White variant
	+ Mk2 reactor NFE mm patch tweaked, should now produce full rated power when using NFE
	+ Ramjet now has gimbal
	+ VTOL engine gimbals restored
	+ Added cockpit IVA ViewTransforms
	+ Model Rework: HS-X cockpit
	+ Model Rework; JE-1 'Mule' turbofan; added size1/mk2 attachment
	+ Banshee reverted to LF/O fuelmode; alternate fuel modes added via MM patches
	+ Banshee thrust buffed slightly
* 2016-1013: 1.7.20 (SuicidalInsanity) for KSP 1.2
	+ Fixes nosebay mesh configuration issue
	+ Update for KSP 1.2
		- Part categories updated to use 1.2 categories
		- New Part: Mk2 Nosecone cargobay
		- Part Rework: Service Tank
		- Part Rework: 2-State Aerospace intake now 2-State Aerospace mount
		- Part Rework; Mk2 Service Bay now has Xenon/MP option
		- Part Rework: Afterburn Ramjet
		- Part Rework: RCSAS module, torque values tweaked
		- Reworked Viper IVA
		- Fixed Dropship cockpit IVA overlaymask clipping
		- Cockpits now have internal antenna modules
		- SC-TD cockpit now has Kerbnet access
		- Mk2 Scilab now has kerbnet access
		- Fixed reactor timewarp bug
		- Fixed Docking Port Editor CtD issue
		- Stationkeeper OMS pod size tweaked
		- Stationkeeper OMS pod new FX
		- RCS units now use new FX
* 2016-0404: 1.7.0.1 (SuicidalInsanity) for KSP 1.05
	+ 1.7.13. See included change log for list of changes
* 2016-0101: 1.7.01-Pre (SuicidalInsanity) for KSP 1.05 PRE-RELEASE
	+ KSP 1.05 dev prerelease for the upcoming KSP 1.1 M2X 1.7 update
* 2015-1112: 1.6.11 (SuicidalInsanity) for KSP 1.0
	+ No changelog provided
* 2015-1001: 1.6.05 (SuicidalInsanity) for KSP 1.0
	+ No changelog provided
* 2015-0924: 1.6 (SuicidalInsanity) for KSP 1.0
	+ No changelog provided
* 2015-0917: 1.5.1 (SuicidalInsanity) for KSP 1.0
	+ No changelog provided
