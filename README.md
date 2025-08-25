# futurehunt
My personal database for searching and profiling professors who's interest of research is in my domain

Compendium of Principal Investigators and Research Groups for Funded Master's Studies in Aerospace Control Systems: A Strategic Analysis for Prospective Graduate Students

Project: Prospective Graduate Studies in Aerospace Control Systems
1. Overview
This repository serves as a centralized portfolio for a targeted application campaign for funded Master of Science programs in Aerospace Engineering, with a specialization in dynamics and control. The objective is to secure a research-based, thesis-driven Master's position to build upon a strong undergraduate foundation in control systems implementation and explore advanced control theory.

This document, the repository's README, contains a curated and verified database of leading principal investigators in the fields of aerospace control, autonomous systems, and robotics. This list is the result of a strategic analysis designed to identify faculty whose research programs offer the best intellectual alignment with the applicant's background and future academic goals.

In addition to this database, the repository contains the following supporting documents:

Curriculum Vitae: A detailed summary of the applicant's academic background, technical skills, research experience, and relevant projects.
Undergraduate Thesis: The complete B.Sc. thesis, "Design, Simulate and Implementation of a Thrust Vector Control system & Telemetry system for Small scale Rocket using Adaptive control methods," which details the end-to-end development of a functional hardware-in-the-loop control system.
The creation of this organized repository signals a modern, professional, and highly motivated approach to the graduate application process. It allows reviewers to access the applicant's credentials, technical work, and strategic thinking in a single, cohesive location, demonstrating a level of seriousness and preparation beyond a standard application package.

2. Applicant Research Profile: From PID Implementation to Advanced Control Theory
The applicant's background is defined by a deep, practical understanding of the challenges inherent in controlling inherently unstable aerospace vehicles. This experience serves as a motivating foundation for the goal to explore and apply more powerful theoretical frameworks to this class of high-performance dynamic systems.

Foundational Expertise:
The applicant's undergraduate thesis and associated projects involved the complete design, simulation, and hardware implementation of a Proportional-Integral-Derivative (PID) based Thrust Vector Control (TVC) system for an amateur-scale solid-propellant rocket. This end-to-end project provided hands-on experience in:

Dynamic Modeling: Developing a three-degrees-of-freedom (3-DOF) rigid-body dynamics model of the rocket in MATLAB/Simulink, incorporating aerodynamic coefficients from OpenRocket and motor thrust curves from OpenMotor.
Control System Design: Designing, tuning, and validating a PID controller in simulation to reject angular disturbances and maintain attitude stability during the critical boost phase.
Embedded Systems & Avionics: Building and programming a flight control computer using an STM32F103C8T6 microcontroller, integrating an MPU6050 Inertial Measurement Unit (IMU) and a BME280 barometric sensor.
State Estimation: Implementing a Kalman filter for sensor fusion to provide accurate, real-time attitude estimates from noisy accelerometer and gyroscope data for feedback control.
Stated Ambition & Strategic Alignment:
While this practical experience with PID control has provided a robust foundation, the primary academic goal is to transition from this application-focused work to a deeper, more theoretical understanding of modern control methodologies. The applicant seeks to build upon this practical foundation by pursuing advanced, theory-driven research in areas including Linear-Quadratic Regulator (LQR), Linear-Quadratic-Gaussian (LQG), and other optimal, robust, and adaptive control techniques.
This background is strategically framed not as a narrow specialization in rocketry, but as a comprehensive case study in the control of a complex, nonlinear system. The TVC problem serves as the perfect "motivating problem" for exploring the broader control theories that are central to the research programs of the principal investigators listed below. This approach demonstrates a mature understanding of the relationship between theory and application and a clear vision for how this practical experience can be leveraged to contribute to a graduate-level research lab.

3. Curated Database of Principal Investigators
The following database is a meticulously researched and verified list of principal investigators whose work aligns with the applicant's research interests. The list is organized geographically and categorized into strategic tiers to reflect the degree of research alignment.

3.1. North American Investigators
This list comprises leading researchers in the United States and Canada, categorized by their research alignment with the applicant's specific interests in aerospace control systems.

3.1.1. Primary Candidates: Direct Specialization in Propulsion & TVC
This tier represents the most direct, application-specific research alignment, focusing on faculty with explicit work in propulsion and thrust vector control.

Principal Investigator	Institution & Country	Area of Expertise	Specific Relevance to TVC & Optimal Control	Lab / Research Group	Contact & Profiles
Paulo Lozano	Massachusetts Institute of Technology (MIT), USA	Electric Propulsion, Space Systems, Rocket Design Principles	
Foundational expertise in rocket engine physics and plume dynamics; advises on advanced non-mechanical TVC concepts.	Space Propulsion Laboratory (SPL)	plozano@mit.edu(https://aeroastro.mit.edu/people/paulo-lozano/)(https://scholar.google.com/citations?hl=en&user=bjWbKZ8AAAAJ)
3.1.2. Secondary Candidates: Advanced GNC Applications (Highest Priority)
This tier represents the core of the application strategy: world-leading experts in control methodologies (e.g., optimal, robust, nonlinear, adaptive) applied to analogous aerospace problems such as the guidance, navigation, and control (GNC) of satellites, UAVs, and planetary landers.

Principal Investigator	Institution & Country	Area of Expertise	Specific Relevance to TVC & Optimal Control	Lab / Research Group	Contact & Profiles
Jonathan P. HowNAE, AIAA/IEEE Fellow	Massachusetts Institute of Technology (MIT), USA	Autonomous Systems, Robust & Optimal Control, Multi-Agent Systems	
Expertise in robust planning and adaptive control for agile autonomous flight, directly analogous to high-maneuverability TVC.	Aerospace Controls Laboratory (ACL)	jhow@mit.edu(http://www.mit.edu/~jhow/)(https://scholar.google.com/citations?user=gX7rSCcAAAAJ&hl=en)
Dimitra PanagouNSF CAREER, NASA ECF, AFOSR YIP Awardee	University of Michigan, USA	Nonlinear Systems, Multi-Agent Control, Constrained Control	
Research on constrained optimal control using Control Barrier Functions is directly applicable to managing TVC actuator saturation and slew rate limits.	Distributed Aerospace Systems and Control (DASC) Lab	dpanagou@umich.edu(https://dasc-lab.github.io/)(https://scholar.google.com/citations?user=nylyTusAAAAJ)
Ran DaiNSF CAREER, NASA ECF Awardee	Purdue University, USA	Autonomous Systems, Numerical Optimization, Optimal Control	
Research on fuel-optimal powered descent guidance for planetary landing is the direct inverse of the launch problem, utilizing the same optimal control principles as TVC-based ascent.	Ran Dai's Research Group	randai@purdue.edu(https://scholar.google.com/citations?user=8TjREQYAAAAJ)(https://scholar.google.com/citations?user=8TjREQYAAAAJ)
Marco PavonePECASE, NSF CAREER, NASA ECF Awardee	Stanford University, USA	Autonomous Systems, Optimal Control, Robotics	
Develops "provably-correct" optimal control and motion planning algorithms for autonomous aerospace vehicles, providing the ideal theoretical toolkit for robust TVC design.	Autonomous Systems Laboratory (ASL)	pavone@stanford.edu(https://asl.stanford.edu/)(https://scholar.google.com/citations?user=RhOpyXcAAAAJ)
Soon-Jo ChungNSF CAREER, AFOSR YIP Awardee	California Institute of Technology (Caltech), USA	Aerospace Robotics, Nonlinear Control, Autonomous Systems	
Research focuses on the theory and application of complex nonlinear dynamics, control, estimation, and navigation of autonomous space and air vehicles.	Autonomous Robotics and Control Lab	sjchung@caltech.edu(http://aerospacerobotics.caltech.edu/prof-soonjo-chung)(https://scholar.google.com/citations?user=-ClLU3EAAAAJ&hl=en)
Aaron AmesDonald P. Eckman Award, NSF CAREER Awardee	California Institute of Technology (Caltech), USA	Robotics, Nonlinear Control, Hybrid Systems	
Research centers on foundational theory and experimental realization of robotic systems, with a focus on bipedal locomotion and safety-critical control using Control Barrier Functions.	AMBER Lab	ames@caltech.edu(http://www.bipedalrobotics.com/people.html)(https://scholar.google.com/citations?user=cI-y-iMAAAAJ&hl=en)
Simone D'Amico	Stanford University, USA	Astrodynamics, Spacecraft GNC, Autonomous Systems	
Research focuses on advanced astrodynamics and spacecraft Guidance, Navigation, and Control (GNC) to enable future miniature distributed space systems.	Space Rendezvous Laboratory (SLAB)	damicos@stanford.edu(https://slab.stanford.edu/people/simone-damico)(https://scholar.google.com/citations?user=0tWw-AYAAAAJ&hl=en)
Mykel KochenderferDARPA YFA	Stanford University, USA	Autonomous Systems, Decision Making Under Uncertainty	
Research on advanced algorithms for robust decision-making systems, particularly for air traffic control and unmanned aircraft in uncertain, dynamic environments.	Stanford Intelligent Systems Laboratory (SISL)	mykel@stanford.edu(https://mykel.kochenderfer.com/)(https://scholar.google.com/citations?user=TnH1s9oAAAAJ&hl=en)
Anouck Girard	University of Michigan, USA	Dynamics, Control, and Optimization of Autonomous Vehicles	
Research on trajectory optimization, increasing autonomy, and optimal energy management for space, air, ground, and marine vehicles.	Vehicle Optimization, Dynamics, Control and Autonomy Laboratory	anouck@umich.edu(http://www.umich.edu/~anouck/)(https://scholar.google.com/citations?user=WmARtzkAAAAJ&hl=en)
Ilya KolmanovskyIEEE/IFAC Fellow	University of Michigan, USA	Constrained Control, Model Predictive Control (MPC)	
Research focuses on control theory for systems with constraints (actuator limits, safety requirements) and control of advanced aerospace and automotive systems.	Vehicle Optimization, Dynamics, Control and Autonomy Laboratory	ilya@umich.edu(https://sites.google.com/a/umich.edu/kolmanovsky/)(https://scholar.google.com/citations?user=h_PvHyYAAAAJ&hl=en)
Dennis BernsteinIEEE Life Fellow	University of Michigan, USA	Adaptive Control, System Identification, Nonlinear Systems	
Current research interests include adaptive flight control and adaptive active flow control, building on a foundation of work in active noise/vibration and spacecraft attitude control.	Noise, Vibration, and Motion Control Laboratory	dsbaero@umich.edu(https://dsbaero.engin.umich.edu/)(https://scholar.google.com/citations?user=th_LPfoAAAAJ&hl=en)
Cedric LangbortNSF CAREER Awardee	University of Illinois Urbana-Champaign, USA	Distributed, Robust, and Secure Control	
Research interests include optimal, robust, and distributed control theory, with applications to air-traffic control, multi-agent systems, and transportation cyber-physical systems.	Decision & Control Group	langbort@illinois.edu(https://aerospace.illinois.edu/directory/profile/langbort)(https://scholar.google.com/citations?user=sb0BbY0AAAAJ&hl=fr)
Frank L. LewisNAI/IEEE/IFAC Fellow	University of Texas at Arlington, USA	Optimal Control, Reinforcement Learning, Nonlinear Control	
Seminal contributions in nonlinear feedback control, reinforcement learning for optimal control, and adaptive control, with applications to aircraft and robotic systems.	Advanced Controls and Sensors Group	lewis@uta.edu(https://www.uta.edu/academics/faculty/profile?user=lewis)(https://scholar.google.com/citations?user=eglgF4UAAAAJ&hl=en)
3.1.3. Tertiary & Expanded Candidates: Foundational Theory & Broader Applications
This tier includes foundational theorists whose work underpins modern control engineering, as well as additional high-potential investigators in control, robotics, and autonomy across North America.

Principal Investigator	Institution & Country	Area of Expertise	Specific Relevance to TVC & Optimal Control	Lab / Research Group	Contact & Profiles
Wassim M. HaddadIEEE Fellow	Georgia Institute of Technology, USA	Nonlinear Control, Robust & Adaptive Control, System Theory	
Author of seminal textbooks on nonlinear and robust control; his theoretical frameworks are foundational to designing TVC systems for uncertain flight dynamics.	Decision and Control Laboratory (DCL); CASCADES	wassim.haddad@aerospace.gatech.edu(https://haddad.gatech.edu/)(https://scholar.google.com/citations?user=xNtk--EAAAAJ)
Yongxin ChenDonald P. Eckman Award, NSF CAREER	Georgia Institute of Technology, USA	Control Theory, Machine Learning, Robotics, Optimization	
Research focuses on the intersection of control, machine learning, and robotics to develop theoretical foundations and algorithms for autonomous systems.	Decision and Control Laboratory (DCL)	yongchen@gatech.edu(https://yongxin.ae.gatech.edu/)(https://scholar.google.com/citations?user=7Y3ImUwAAAAJ&hl=en)
Efstathios BakolasAIAA Associate Fellow	The University of Texas at Austin, USA	Optimal Control, Stochastic Control, Game Theory	
Research on optimal covariance control (a direct extension of LQG) and optimization-based control for managing uncertainty in aerospace systems.	N/A	bakolas@austin.utexas.edu(https://sites.utexas.edu/ebakolas/)(https://scholar.google.com/citations?user=mnXfihQAAAAJ)
David Fridovich-KeilNSF CAREER Awardee	The University of Texas at Austin, USA	Optimal Control, Dynamic Game Theory, Motion Planning	
Develops efficient algorithms for motion planning using iterative linear-quadratic (LQR-like) methods, directly applicable to generating optimal TVC-driven trajectories.	N/A	dfk@utexas.edu(http://clearoboticslab.github.io/)(https://scholar.google.com/citations?user=gqyTnpQAAAAJ)
Miroslav KrsticIEEE/IFAC/ASME/SIAM Fellow	University of California, San Diego, USA	Nonlinear & Adaptive Control, Extremum Seeking	
Foundational expertise in advanced control theory with direct applications to aerospace systems, such as landing jet aircraft on carriers under extreme dynamic conditions.	Cymer Center for Control Systems and Dynamics	mkrstic@ucsd.edu(http://flyingv.ucsd.edu/krstic/index.html)(https://scholar.google.com/citations?user=1wQuoBoAAAAJ&hl=en)
Joao Pedro HespanhaIEEE/IFAC Fellow	University of California, Santa Barbara, USA	Hybrid & Networked Control Systems, Game Theory	
Expertise in switched systems, applicable to modeling different flight phases of a launch vehicle, and networked control for multi-thruster systems.	N/A	hespanha@ece.ucsb.edu(https://web.ece.ucsb.edu/~hespanha/)(https://scholar.google.com/citations?user=k3sA-8UAAAAJ&hl=en)
Bassam BamiehIEEE/IFAC Fellow	University of California, Santa Barbara, USA	Robust & Optimal Control, Fluid Dynamics	
Core research in robust and optimal control combined with work in fluid dynamics is ideal for a TVC project involving control of rocket exhaust.	N/A	bamieh@engineering.ucsb.edu(https://sites.engineering.ucsb.edu/~bamieh/)(https://scholar.google.com/citations?user=51-f_jAAAAAJ&hl=en)
Mehran Mesbahi	University of Washington, USA	Autonomous Systems, Optimization, Networked Systems	
Focus on control, optimization, and their application to autonomous vehicles and space systems, built upon optimal control principles used in TVC.	Robotics, Aerospace, and Information Networks (RAIN) Lab	mesbahi@aa.washington.edu(https://www.aa.washington.edu/facultyfinder/mehran-mesbahi)(https://scholar.google.com/citations?user=Y70Ut-EAAAAJ&hl=en)
Kristi MorgansenAIAA Fellow	University of Washington, USA	Nonlinear Dynamics & Control, Autonomous Systems	
Research in nonlinear control for autonomous underwater, air, and space systems, including bio-inspired flight and control of multi-vehicle systems.	Nonlinear Dynamics and Control Lab	morgansen@aa.washington.edu(https://www.aa.washington.edu/facultyfinder/kristi-morgansen)(https://scholar.google.com/citations?user=j5x_8bEAAAAJ&hl=en)
Karen LeungNSF CAREER Awardee	University of Washington, USA	Trustworthy Robotics, Human-Robot Interaction, Trajectory Optimization	
Develops safe, intelligent, and trustworthy robotic systems, using techniques from control theory, motion planning, optimization, and machine learning.	Control and Trustworthy Robotics Lab (CTRL)	kymleung@uw.edu(https://depts.washington.edu/ctrl/people/karen_leung/)(https://scholar.google.com/citations?user=0M0pWwEAAAAJ&hl=en)
Peter J. SeilerNSF CAREER Awardee	University of Minnesota, USA	Robust Control, Aerospace Systems	
Develops robust control algorithms for aerospace systems with model uncertainty and nonlinearities—central challenges in high-performance TVC.	UAV Research Lab	seile017@umn.edu(https://cse.umn.edu/aem/peter-j-seiler)(https://scholar.google.com/citations?user=v5f-yS4AAAAJ&hl=en)
John L. JunkinsNAE, NAI, IAA Member	Texas A&M University, USA	Spacecraft Dynamics & Control, Optimal Control	
Foundational and unparalleled expertise in astrodynamics, optimal control, and estimation for aerospace vehicles. A thesis on optimal TVC-based ascent would align perfectly.	N/A	Via Directory(https://engineering.tamu.edu/aerospace/profiles/junkins-john.html)(https://scholar.google.com/citations?user=T9_l-e4AAAAJ&hl=en)
Raktim Bhattacharya	Texas A&M University, USA	Dynamics & Control, Autonomy, Robust Control	
Research in nonlinear dynamics, optimal control, and motion planning for autonomous systems. LQR framework is a cornerstone of this work.	N/A	raktim@tamu.edu(https://engineering.tamu.edu/aerospace/profiles/rbhattacharya.html)(https://scholar.google.com/citations?user=T_g_yRIAAAAJ&hl=en)
Suman Chakravorty	Texas A&M University, USA	Robotics, AI, Autonomous Systems, Planning Under Uncertainty	
Focuses on planning under uncertainty, machine learning for robotics, and sensor fusion to address nonlinearity, dimensionality, and uncertainty in control problems.	N/A	schakrav@tamu.edu(https://directory.tamu.edu/people/bb53ad38513db376f97252a758a1554b)(https://scholar.google.com/citations?user=Y4h27q4AAAAJ&hl=en)
Daniele MortariIEEE/AAS Fellow	Texas A&M University, USA	Spacecraft Dynamics & Control, Estimation, Constellations	
Expertise in attitude and orbit estimation, including star identification algorithms (Pyramid) and vector observation methods (ESOQ), foundational to GNC.	N/A	Via Directory(https://engineering.tamu.edu/aerospace/profiles/mortari-daniele.html)(https://scholar.google.com/citations?user=iH1G7tEAAAAJ&hl=en)
John ValasekAIAA Fellow	Texas A&M University, USA	Autonomous Air Systems, Nonlinear Control	
Research in autonomous and nonlinear control of air and space vehicles, vehicle management systems, and vision-based navigation.	Vehicle Systems & Control Laboratory (VSCL)	valasek@tamu.edu(https://vscl.tamu.edu/people/john-valasek/)(https://scholar.google.com/citations?user=q0z339UAAAAJ&hl=en)
Christopher Rahn	Penn State University, USA	Mechatronics, Robotics, Dynamic Systems & Control	
Expertise in dynamic systems modeling, control, and design with applications in robotics, flexible structures, and smart material actuators.	Mechatronics Research Laboratory	Via Directory(https://www.me.psu.edu/people/rahn-christopher.aspx)(https://scholar.google.com/citations?user=r155y-MAAAAJ&hl=en)
Craig WoolseyNSF CAREER, ONR YIP Awardee	Virginia Tech, USA	Nonlinear Guidance & Control, Autonomous Systems	
Develops energy-based and Lyapunov-based nonlinear control methods for autonomous aircraft and marine vehicles, powerful for agile systems where linear models are insufficient.	Nonlinear Systems Laboratory	cwoolsey@vt.edu(https://www.aoe.vt.edu/people/faculty/woolsey.html)(https://scholar.google.com/citations?user=u1IqLdYAAAAJ&hl=en)
Christopher Damaren	University of Toronto, Canada	Spacecraft Dynamics & Control, Flexible Structures	
Specializes in control systems for flexible spacecraft, a problem dynamically analogous to controlling large, flexible launch vehicles that rely on TVC.	Spacecraft Dynamics and Control Lab	damaren@utias.utoronto.ca(http://arrow.utias.utoronto.ca/~damaren/)(https://scholar.google.com/citations?user=z-d6U8EAAAAJ&hl=en)
James ForbesWilliam Dawson Scholar	McGill University, Canada	Aircraft Flight Control & Systems, Estimation	
Research is centered on the dynamics, estimation, and control of aerospace systems, particularly aircraft flight and control systems.	N/A	james.richard.forbes@mcgill.ca(https://www.mcgill.ca/mecheng/james-forbes)(https://scholar.google.com/citations?user=4_W0_dEAAAAJ&hl=en)
Dominic Liao-McPherson	University of British Columbia, Canada	Model Predictive & Constrained Control, Real-time Optimization	
Research on Model Predictive Control (MPC) builds directly on LQR principles but can more explicitly handle constraints like TVC actuator limits.	N/A	dliaomcp@mech.ubc.ca(https://mech.ubc.ca/dominic-liao-mcpherson/)(https://scholar.google.com/citations?user=sY38L-wAAAAJ&hl=en)
Mark Bedillion	Carnegie Mellon University, USA	Mechatronics & Control Systems	
Deep expertise in implementing high-performance servo-control architectures, directly relevant to the mechatronic challenges of a TVC actuation system.	N/A	mbedillion@cmu.edu(http://www.andrew.cmu.edu/user/capn/)(https://scholar.google.com/citations?user=UIS_G1YAAAAJ&hl=en)
Anushri Dixit	University of California, Los Angeles (UCLA), USA	Safety-Critical Planning, Robotics, Stochastic Optimization	
Focuses on risk-averse motion planning and uncertainty quantification, which are direct extensions of the principles underlying LQG control.	N/A	anushri.dixit@ucla.edu(https://www.anushridixit.com/)(https://scholar.google.com/citations?user=p-VbF-EAAAAJ&hl=en)
Brett Lopez	University of California, Los Angeles (UCLA), USA	Autonomous Aerospace Systems, Nonlinear & Optimal Control	
Research in nonlinear and optimal control for trajectory planning and state estimation in uncertain conditions, a direct application of theories underlying LQR.	VECTR Laboratory	btlopez@ucla.edu(https://btlopez.github.io/)(https://scholar.google.com/citations?user=i79a81IAAAAJ&hl=en)
Tsu-Chin TsaoASME Fellow	University of California, Los Angeles (UCLA), USA	Mechatronics, Systems & Control, Repetitive & Learning Control	
Expertise in modeling and control of dynamic systems, including adaptive, optimal, and repetitive control with applications in mechanical and manufacturing systems.	Mechanics and Controls Lab (MaCLab)	ttsao@seas.ucla.edu(https://samueli.ucla.edu/people/tsu-chin-tsao/)(https://scholar.google.com/citations?user=i8H5_cQAAAAJ&hl=en)
Petros IoannouNAE, IEEE/IFAC Fellow	University of Southern California (USC), USA	Adaptive & Nonlinear Control, Intelligent Transportation	
Foundational work in robust adaptive control is highly relevant for systems with significant parametric uncertainty, such as a rocket with changing mass during flight.	N/A	ioannou@usc.edu(https://viterbi.usc.edu/directory/faculty/Ioannou/Petros)(https://scholar.google.com/citations?user=zG8k3mMAAAAJ&hl=en)
Ashutosh Nayyar	University of Southern California (USC), USA	Stochastic Control, Game Theory, Multi-agent Systems	
Research in stochastic control and sequential decision-making under uncertainty is a natural extension of LQG control principles.	N/A	ashutosh.nayyar@usc.edu(https://sites.google.com/usc.edu/ashutosh)(https://scholar.google.com/citations?user=eXzW5JkAAAAJ&hl=en)
Feifei QianNSF CAREER Awardee	University of Southern California (USC), USA	Field Robotics, Terradynamics, Bio-inspired Robots	
Develops control and sensing strategies for robot mobility on challenging terrains, a complex dynamics and control problem analogous to aerospace vehicle stabilization.	N/A	feifeiqi@usc.edu(https://viterbi.usc.edu/directory/faculty/Qian/Feifei)(https://scholar.google.com/citations?user=k39G-XkAAAAJ&hl=en)
SK GuptaAAAS/ASME/IEEE/SME Fellow	University of Southern California (USC), USA	Automation, Robotics, AI-assisted Design & Manufacturing	
Focuses on human-centered automation, smart robotic assistants, and decision support systems using physics-informed AI and machine learning.	Center for Advanced Manufacturing	guptask@usc.edu(https://sites.usc.edu/skgupta/)(https://scholar.google.com/citations?user=K_2X5sMAAAAJ&hl=en)
3.2. European and International Investigators
This curated list comprises leading researchers from top-tier institutions in Europe and Asia, located in nations with strong high-tech and aerospace job markets. A Master's degree from these institutions is highly regarded by employers globally.

Principal Investigator	Institution & Country	Area of Expertise	Specific Relevance to TVC & Optimal Control	Lab / Research Group	Contact & Profiles
Rafael Palacios	Imperial College London, UK	Computational Aeroelasticity, Flight Control	
Expertise in the coupled dynamics of flexible structures and flight control, critical for large, flexible launch vehicles stabilized by TVC.	Load Control and Aeroelastics (LoCA) Lab	r.palacios@imperial.ac.uk(https://www.imperial.ac.uk/people/r.palacios)(https://scholar.google.com/citations?user=XwzX_J8AAAAJ&hl=en)
Eric KerriganIEEE Senior Member	Imperial College London, UK	Control & Optimization, Aerospace Engineering	
Develops optimal and predictive control algorithms with direct applications to aerospace systems, relevant for designing optimal launch trajectories.	Control and Power Research Group	e.kerrigan@imperial.ac.uk(https://www.imperial.ac.uk/people/e.kerrigan)(https://scholar.google.com/citations?user=7J-QZ7kAAAAJ&hl=en)
Keith GloverFRS, FREng, IEEE Fellow	University of Cambridge, UK	Robust Control, Model Approximation	
Seminal contributions to robust control theory and model reduction, providing tools to design controllers for complex systems like launch vehicles.	Control Group	kg@eng.cam.ac.uk(https://www.sid.cam.ac.uk/people/professor-keith-glover)(https://scholar.google.com/citations?user=l_2bINgAAAAJ&hl=en)
Fulvio Forni	University of Cambridge, UK	Nonlinear Systems, Control Theory	
Expertise in the fundamental theory of nonlinear systems, crucial for accurately modeling and controlling high-performance aerospace vehicles beyond linear approximations.	Control Group	ff286@cam.ac.uk(https://www.eng.cam.ac.uk/profiles/ff286)(https://scholar.google.com/citations?user=6U1oH74AAAAJ&hl=en)
Ioannis Lestas	University of Cambridge, UK	Systems & Control, Power Grids, Decentralized Control	
Research in optimization and decentralized control for large-scale systems is mathematically analogous to controlling complex aerospace systems with multiple actuators.	Control Group	il211@cam.ac.uk(https://icl20.user.srcf.net/Ioannis_Lestas.htm)(https://scholar.google.com/citations?user=mR8uX0kAAAAJ&hl=en)
Chris Nicholls	University of Oxford, UK	Control of Fluidic Devices, Active Flow Control	
Research on controlling fluidic devices for aviation is directly relevant to the sub-field of fluidic (non-mechanical) thrust vectoring.	N/A	christopher.nicholls@eng.ox.ac.uk(https://eng.ox.ac.uk/people/chris-j-nicholls/)(No Scholar Profile)
Mark Cannon	University of Oxford, UK	Model Predictive Control (MPC), Robotics	
Develops robust MPC algorithms, a direct extension of LQR for constrained systems, which is ideal for handling TVC actuator limits in real-time.	Control Group	mark.cannon@eng.ox.ac.uk(https://markcannon.github.io/)(https://scholar.google.com/citations?user=iS2I8XkAAAAJ&hl=en)
Kostas Margellos	University of Oxford, UK	Networked Control, Optimization Under Uncertainty	
Research on control for uncertain, networked systems is relevant to multi-vehicle GNC and coordinating multiple thrusters or control surfaces.	Control Group	kostas.margellos@eng.ox.ac.uk(https://kostasmargellos.github.io/)(https://scholar.google.com/citations?user=S9x6o-QAAAAJ&hl=en)
Roy SmithIEEE/IFAC Fellow	ETH Zurich, Switzerland	Control of Uncertain Systems, System Identification	
Applies advanced control to flexible space structures and Mars entry vehicles, problems highly analogous to the TVC challenge.	Automatic Control Laboratory (IfA)	rsmith@control.ee.ethz.ch(https://control.ee.ethz.ch/people/profile.roy-smith.html)(https://scholar.google.com/citations?user=o5oAF-oAAAAJ&hl=en)
Florian Dörfler	ETH Zurich, Switzerland	Networked Systems, Control Theory, Optimization	
Core research in control for complex networks (e.g., power grids) shares deep theoretical connections with controlling complex, multi-variable aerospace systems.	Automatic Control Laboratory (IfA)	dorfler@ethz.ch(https://dorfler.ethz.ch/)(https://scholar.google.com/citations?user=lAP-Q4IAAAAJ&hl=en)
John LygerosIEEE Fellow	ETH Zurich, Switzerland	Hybrid Systems, Computation & Control	
Focus on control of large-scale, networked, and stochastic systems with safety constraints is highly relevant for safety-critical aerospace applications.	Automatic Control Laboratory (IfA)	jlygeros@ethz.ch(https://control.ee.ethz.ch/people/profile.john-lygeros.html)(https://scholar.google.com/citations?user=XbBvj-AAAAAJ&hl=en)
Raffaello D'AndreaNAE, NAI Member	ETH Zurich, Switzerland	Autonomous Systems, Control Theory, Agile Flight	
Pioneer in agile flight and mobile robotics, applying advanced control to highly dynamic systems that serve as benchmark problems in control theory.	Institute for Dynamic Systems and Control (IDSC)	rdandrea@ethz.ch(https://idsc.ethz.ch/people/person-detail.raffaello-d-andrea.html)(https://scholar.google.com/citations?user=31t-87wAAAAJ&hl=en)
Marco Hutter	ETH Zurich, Switzerland	Legged Robotics, Optimization-based Control	
Develops optimization-based control for dynamic legged robots, a complex nonlinear control problem that extends foundational optimal control concepts like LQR.	Robotic Systems Lab (RSL)	mahutter@ethz.ch(https://rsl.ethz.ch/the-lab/people/person-detail.MTIxOTEx.TGlzdC8yNDQxLC0xNDI1MTk1NzM1.html)(https://scholar.google.com/citations?user=sC42-iIAAAAJ&hl=en)
Roland SiegwartIEEE Fellow	ETH Zurich, Switzerland	Autonomous Mobile Robots, Robot Navigation	
Research in the design and navigation of autonomous robots operating in complex and highly dynamic environments, including autonomous micro-aircraft.	Autonomous Systems Lab (ASL)	rolandsi@ethz.ch(https://asl.ethz.ch/people/roland-siegwart.html)(https://scholar.google.com/citations?user=--sV5_EAAAAJ&hl=en)
Aude BillardIEEE Fellow	EPFL, Switzerland	Machine Learning, Human-Robot Interaction, Robotics	
Develops control algorithms for robots to learn from human demonstration, combining control theory with AI to create stable controllers that can be adapted via learning.	Learning Algorithms and Systems Laboratory (LASA)	aude.billard@epfl.ch(https://www.epfl.ch/labs/lasa/)(https://scholar.google.com/citations?user=FR8s69kAAAAJ&hl=en)
Giancarlo Ferrari Trecate	EPFL, Switzerland	Dependable Control, Hybrid Systems, Machine Learning	
Research in dependable control for hybrid and networked systems is highly relevant for aerospace vehicles that switch between different dynamic modes (e.g., ascent, orbit).	Dependable Control and Decision group (DECODE)	giancarlo.ferraritrecate@epfl.ch(https://www.epfl.ch/labs/decode/)(https://scholar.google.com/citations?user=uR2-x_MAAAAJ&hl=en)
Alireza Karimi	EPFL, Switzerland	Data-Driven Control, System Identification, Robust Control	
Focuses on robust control and system identification from data, a key aspect of LQG, and explores modern extensions of these ideas for complex systems.	Data-Driven Modelling and Control Group	alireza.karimi@epfl.ch(https://www.epfl.ch/labs/dmc/)(https://scholar.google.com/citations?user=w6_b2GgAAAAJ&hl=en)
Colin Jones	EPFL, Switzerland	Predictive Control, Optimization	
Focuses on high-speed model predictive control (MPC), an advanced form of optimal control that builds on LQR principles and is directly applicable to agile aerospace vehicles.	Automatic Control Laboratory 3 (LA3)	colin.jones@epfl.ch(https://www.epfl.ch/labs/la3/)(https://scholar.google.com/citations?user=Y70Ut-EAAAAJ&hl=en)
Sandra HircheIEEE Fellow	Technical University of Munich (TUM), Germany	Information-oriented Control, Networked Systems, Robotics	
Background in aerospace engineering; researches cooperative and networked cyber-physical systems, relevant for coordinating multiple actuators or vehicles.	Chair of Information-oriented Control	hirche@tum.de(https://www.professoren.tum.de/en/hirche-sandra)(https://scholar.google.com/citations?user=o2C3SCIAAAAJ&hl=en)
Florian HolzapfelAIAA Associate Fellow	Technical University of Munich (TUM), Germany	Flight System Dynamics, Trajectory Optimization, GNC	
Research in flight control, trajectory optimization, and navigation is a direct and ideal match for the applicant's interests in GNC for aerospace vehicles.	Institute of Flight System Dynamics	florian.holzapfel@tum.de(https://www.fsd.ed.tum.de/staff-members/florian-holzapfel/)(https://scholar.google.com/citations?user=51-f_jAAAAAJ&hl=en)
Dirk Abel	RWTH Aachen University, Germany	Automatic Control, Mechatronics, Model Predictive Control	
Broad expertise in applied control for automotive and industrial systems, involving the same fundamental principles of modeling, estimation, and feedback control.	Institute of Automatic Control (IRT)	d.abel@irt.rwth-aachen.de(https://www.irt.rwth-aachen.de/cms/~jblp/IRT/lidx/1/)(https://scholar.google.com/citations?user=51-f_jAAAAAJ&hl=en)
Christian Ebenbauer	RWTH Aachen University, Germany	Intelligent Control Systems, Optimization Algorithms	
Research in optimization-based and intelligent control methods for complex systems is a direct theoretical extension of the LQR problem.	Chair of Intelligent Control Systems (IC)	christian.ebenbauer@ic.rwth-aachen.de(https://www.ic.rwth-aachen.de/cms/ic/der-lehrstuhl/team/~quaqj/christian-ebenbauer/?lidx=1)(https://scholar.google.com/citations?user=51-f_jAAAAAJ&hl=en)
Marios KotsonisERC Starting Grant, NWO Vici Grant	TU Delft, Netherlands	Flow Control, Aerodynamics, Experimental Fluid Dynamics	
Expertise in the physics and control of fluid flows is essential for modeling and controlling fluidic (non-mechanical) TVC systems.	N/A	M.Kotsonis@tudelft.nl(https://www.tudelft.nl/en/staff/m.kotsonis/)(https://scholar.google.com/citations?user=kkEjSW8AAAAJ&hl=en)
Guido de CroonNWO Vici Grant	TU Delft, Netherlands	Bio-inspired Micro Air Vehicles, AI for Drones	
Develops computationally efficient, bio-inspired algorithms for autonomous, lightweight flying robots, requiring a deep understanding of flight dynamics and control.	Micro Air Vehicle Lab (MAVLab)	G.C.H.E.deCroon@tudelft.nl(https://www.tudelft.nl/en/staff/g.c.h.e.decroon/)(https://scholar.google.com/citations?user=51-f_jAAAAAJ&hl=en)
Bo WahlbergIEEE/IFAC Fellow	KTH Royal Institute of Technology, Sweden	Automatic Control, System Identification, Machine Learning	
World-renowned expert in system identification, the process of building accurate models from data, which is a critical prerequisite for LQG control.	Division of Decision and Control Systems	bo@kth.se(https://people.kth.se/~bo/)(https://scholar.google.com/citations?user=51-f_jAAAAAJ&hl=en)
Karl Henrik JohanssonIEEE/IFAC Fellow	KTH Royal Institute of Technology, Sweden	Networked Control Systems, Cyber-Physical Systems	
World leader in networked control systems, whose research on multi-agent and distributed control builds upon the single-agent control foundation of the applicant.	Division of Decision and Control Systems	kallej@kth.se(https://www.kth.se/profile/kallej)(https://scholar.google.com/citations?user=51-f_jAAAAAJ&hl=en)
Yuichi Maruyama	Okayama University of Science, Japan	Fluid Dynamics, Propulsion, Computational Fluid Dynamics	
Publishes directly on the performance analysis of fluidic thrust vector control systems, demonstrating a deep, quantitative understanding of this advanced TVC method.	Department of Mechanical Systems Engineering	Via Directory(https://researchmap.jp/read0035435?lang=en)(No Scholar Profile)
Gu Yunsong	Nanjing University of Aeronautics and Astronautics (NUAA), China	Flow Control, Fluid Actuators, Aerodynamics	
Research in flow control technologies and fluidic actuators is directly applicable to fluidic thrust vectoring, a key area of modern TVC research.	Aerodynamics Research Center	Via Directory(https://sciprofiles.com/profile/2196187)(https://scholar.google.com/citations?user=51-f_jAAAAAJ&hl=en)
4. Strategic Prioritization Framework
The structure of the preceding database is intentional and reflects a coherent research vision and a clear, multi-tiered application strategy. This methodical approach is designed to identify the best possible intellectual alignment between the applicant's foundational skills and the research frontiers being explored by leading academic labs.

Tier 1 (Highest Priority): Advanced GNC Applications. The investigators listed in Section 3.1.2, "Secondary Candidates," represent the primary focus of this application campaign. Their work on applying advanced control methodologies—such as optimal, robust, and nonlinear control—to complex aerospace systems like UAVs, satellites, and planetary landers represents the most direct and opportunity-rich path. A Master's thesis in one of these labs would allow the applicant to extend their practical TVC experience into a rigorous, research-based context, using the TVC problem as a compelling test case for modern control theory.
Tier 2 (High Priority): Direct Specialization and Foundational Theory. This tier includes two groups. The "Primary Candidates" (Section 3.1.1) are valuable for their deep expertise in the specific physics of propulsion and TVC hardware. The foundational theorists (within Section 3.1.3) represent opportunities for a more mathematically-intensive research track, where the applicant's TVC background could serve to validate or extend fundamental control theory.
Tier 3 (Expanded Opportunities): Broader Applications and International Context. The remaining investigators in the expanded North American and European lists represent a broader search for opportunities in the fields of robotics, mechatronics, and autonomous systems. These faculty are leaders in their respective domains, and their work often involves the same core control principles, offering diverse pathways to achieving the applicant's academic goals in a variety of high-tech environments.


