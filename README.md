# Packed Bed Membrane Reactor Simulation
A one dimensional model for a Packed Bed Membrane Reactor (PBMR) was developed following the next hypothesis: 

-steady state
-isothermal operation  
-plug flow. 

The membrane was considered to be inert. A pseudo homogeneous model was assumed for the packed bed (retentate side). For the permeate side two configurations were analysed:  co-current and counter-current. In order to validate the model, experimental data and kinetics were collected from Gallucci et al.(1) The set of ordinary differential equations was solved using a Runge-Kutta-Fehlberg numerical method implemented in Python. 

For the counter-current mode, the shooting method was used. A good agreement between the simulation results and literature data was found. Once validated, a numerical experiment was performed with the two sets of permeances given in Table 1, and the kinetics from Bussche et al.(2) First, a Packed Bed Reactor (PBR) model was tested allowing the permeances to be zero. Second, the PBMR model in co- and counter-current configurations were simulated. The experimental permeances were collected from a Linde Type A zeolite tested in the Aragon Institute of Engineering Research. 

Graphical schemes:
![imagen](https://user-images.githubusercontent.com/96077675/150651493-b5505247-f6ca-4bca-a7f7-6d0322b05aa3.png)

References:

1. Bussche KV, Froment G. A Steady-State Kinetic Model for Methanol Synthesis and the Water Gas Shift Reaction on a Commercial Cu/ZnO/Al2O3Catalyst. Journal of Catalysis. 1996;161(1):1-10.
2. Gallucci F, Paturzo L, Basile A. An experimental study of CO2 hydrogenation into methanol involving a zeolite membrane reactor. Chemical Engineering and Processing: Process Intensification. 2004;43(8):1029-36.
3. Barbieri G, Marigliano G, Golemme G, Drioli E. Simulation of CO2 hydrogenation with CH3OH removal in a zeolite membrane reactor. Chemical Engineering Journal. 2002;85(1):53-9.

Some interesting results:
1. Comparison of the effect of experimental and theoretical permeances on the performance of a packed bed membrane reactor in co-current and counter current configuration. Theoretical permeances from Barbieri et. al (3).

![imagen](https://user-images.githubusercontent.com/96077675/150651654-ae35cb58-4ed5-4f78-bc12-8d43bb6c2ffe.png)

2. Effect of the reaction conditions on methanol yield from CO2 and H2 in a packed bed membrane reactor.

![imagen](https://user-images.githubusercontent.com/96077675/150651743-d42988c6-49f3-451e-8ba9-b4a1d764c231.png)

3. Simulation of Packed Bed Membrane Reactors for Methanol Synthesis from CO2 and H2: Suitable Alternatives to Packed Bed Reactor Technology.
![imagen](https://user-images.githubusercontent.com/96077675/150651823-3db74c10-6e26-4288-b19a-7737bdaa5a35.png)


