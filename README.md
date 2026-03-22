# Route optimizer 

### App description 

### Flow 
1. User should provide start and finish point (integration with some app to find addresses)
2. User provide input data: manually write addresses OR scan the picture OR voice message 
3. System sends data to agent integrated with google maps 
4. As an output user gets link to  created google maps route (THE MOST OPTIMAL)

### Implementation steps 
> [PHASE_1] Create very basic concept without GUI:
a) hardcode start and end location 
b) hardcode coordinates of locations 
c) create agent integrated with google 
d) return google maps link with route 


> [PHASE_2] Allow real input (manually only)
a) start and location from some addresses API 
b) use same API to find coordinates of route locations 
c) Use existing agent 

> [PHASE_3] Allow agent read also pictures as and input and find the addresses
a) Read locations from picture
... same 

> [PHASE_4] Create GUI 
a) Think about technologies...

> [PHASE_5] Security 

> [PHASE_6] Deploy it ONLINE 