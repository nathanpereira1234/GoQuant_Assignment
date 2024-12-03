# GoQuant_Assignment
Objective 
Create a high-performance order execution and management system to trade on Deribit Test (https://test.deribit.com/) using C++. 

Initial Setup 
1. Create a new Deribit Test account 
2. Generate API Keys for authentication 

  
Core Requirements:

Order Management Functions 
1. Place order 
2. Cancel order 
3. Modify order 
4. Get orderbook 
5. View current positions 
6. Real-time market data streaming via WebSocket 
   - Implement WebSocket server functionality 
   - Allow clients to subscribe to symbols 
   - Stream continuous orderbook updates for subscribed symbols 

Market Coverage 
- Instruments: Spot, Futures, and Options 
- Scope: All supported symbols 

Technical Requirements 
1. Implementation must be in C++ 
2. System should demonstrate low-latency performance 
3. Include proper error handling and logging 
4. Implement WebSocket server for real-time data distribution 
   - Connection management 
   - Subscription handling 
   - Efficient message broadcasting 

Bonus Section (recommended): Performance Analysis and
Optimization 

Latency Benchmarking 
1. Measure and document the following metrics: 
   - Order placement latency 
   - Market data processing latency 
   - WebSocket message propagation delay 
   - End-to-end trading loop latency 

Optimization Requirements 
1. Implement and justify optimization techniques for: 
   - Memory management 
   - Network communication 
   - Data structure selection 
   - Thread management 
   - CPU optimization 

Documentation Requirements for Bonus Section 
1. Detailed analysis of bottlenecks identified 
2. Benchmarking methodology explanation 
3. Before/after performance metrics 
4. Justification for optimization choices 
5. Discussion of potential further improvements 

Deliverables 
1. Complete source code with documentation 
2. Video recording demonstrating: 
   - System functionality 
   - Code review 
   - Implementation explanation 
3. If completing bonus section: 
   - Performance analysis report 
   - Benchmarking results 
   - Optimization documentation
