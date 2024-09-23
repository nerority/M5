<div align="center">
  <h1>M5 Model</h1>
  <h3>Transcend Traditional Diagramming</h3>
  <h4><i>The M5 Model is achieved with nothing but a system prompt.</i></h4>
  <a href="https://nerority.webflow.io/public/home"><kbd>🟢 Website</kbd></a>
  <a href="https://discord.gg/jBKjsqA6pb"><kbd> ⚪ Discord </kbd></a>
  <a href="https://www.patreon.com/Nerority"><kbd> 🔴 Patreon </kbd></a>
  <br>
  <a href="https://github.com/nerority/Prompt-Engineering-Mastery"><kbd>Prompt Engineering</kbd></a>
  <a href="https://github.com/nerority/Advanced-GPTs"><kbd>Advanced GPTs</kbd></a>
  <a href="https://github.com/nerority/AI-Library"><kbd>Template Library</kbd></a>
  <h3><i>By Devin Pellegrino</i></h3>
</div>

<p align="center">
  <img src="https://github.com/user-attachments/assets/82003f5f-38c8-463b-8377-b7561326ddb1" alt="M5 Logo" width="70%"/>
</p>

---

## Introduction

### What is M5?

M5 (Mermaid Meta-Modeling Master Model) is a cutting-edge AI-powered visualization system designed to transcend traditional diagramming techniques. It leverages the power of Mermaid.js to create dynamic, multi-layered visualizations that capture complex relationships, reveal emergent patterns, and facilitate deep knowledge exploration.

### Key Concepts

- **Hyperspace Projection:** A multi-dimensional framework for organizing and navigating complex knowledge spaces.
- **Cognitive Synergy:** Bridging the gap between human intuition and AI-driven analysis.
- **Adaptive Complexity:** Tailoring visualizations to match user expertise and cognitive load.

## Features

- **Autopilot Mode (M5-APM):** Intuitive, natural language-driven visualization generation.
- **Advanced Mode (M5-ADV):** Precise control over visualization parameters using the Master Function (!M5).
- **Multi-layered Visualizations:** Generate interconnected diagram sets offering diverse perspectives and levels of detail.
- **Knowledge Integration:** Seamlessly incorporate domain-specific ontologies and best practices in visual knowledge representation.
- **Continuous Learning:** Evolve and improve through user feedback and self-reflection.

## Getting Started

**Token Size:** ~97,000

### Supported Models:

- Anthropic Sonnet 3.5
- Google Gemini 1.5

To activate M5, upload or paste the file to the supported LLM, and use the following command:

```
!start M5
```

![image](https://github.com/user-attachments/assets/d6ec1108-839f-4b97-bf83-3037da59de6a)


## Usage

### Autopilot Mode (M5-APM)

Simply describe what you want to visualize in natural language:

```
Model the flow of information in a social network
```

### Advanced Mode (M5-ADV)

Use the Master Function for granular control:

```
!M5("Model", {"System Architecture", "Process Flow"}, {"Granularity: High"}, {"E-commerce Platform"})
```

## Examples: M5 In Action

---

### Personal Finance Visualization: Budget Breakdown and Spending Trends

*This example demonstrates how M5 can help users understand their financial situation, track spending habits, and plan for the future.*

**User:** Provides financial data to analyze.

**M5:** Sounds good. First, we'll create a multi-layered visualization that offers both a high-level overview and detailed insights.

```mermaid
pie title Monthly Budget Allocation
    "Housing" : 30
    "Transportation" : 15
    "Food" : 15
    "Utilities" : 10
    "Entertainment" : 10
    "Savings" : 15
    "Miscellaneous" : 5
```

This high-level overview provides a quick glance at budget allocation across major categories. Now, let's dive deeper into each category and analyze spending trends.

```mermaid
graph TD
    subgraph Income
        I[Total Income] --> IS[Salary]
        I --> IB[Bonuses]
        I --> II[Investments]
    end

    subgraph Expenses
        E[Total Expenses] --> EH[Housing]
        E --> ET[Transportation]
        E --> EF[Food]
        E --> EU[Utilities]
        E --> EE[Entertainment]
        E --> EM[Miscellaneous]

        EH --> EHR[Rent/Mortgage]
        EH --> EHI[Insurance]
        EH --> EHM[Maintenance]

        ET --> ETC[Car Payment]
        ET --> ETG[Gas]
        ET --> ETM[Maintenance]
        ET --> ETP[Public Transport]

        EF --> EFG[Groceries]
        EF --> EFD[Dining Out]

        EU --> EUE[Electricity]
        EU --> EUW[Water]
        EU --> EUI[Internet]
        EU --> EUP[Phone]

        EE --> EEM[Movies/Shows]
        EE --> EEH[Hobbies]
        EE --> EET[Travel]

        EM --> EMC[Clothing]
        EM --> EMH[Healthcare]
        EM --> EME[Education]
    end

    subgraph Savings
        S[Total Savings] --> SE[Emergency Fund]
        S --> SR[Retirement]
        S --> SG[Short-term Goals]
        S --> SL[Long-term Goals]
    end

    I --> E
    I --> S

    classDef income fill:#a8d08d,stroke:#82b366;
    classDef expenses fill:#f8cecc,stroke:#b85450;
    classDef savings fill:#dae8fc,stroke:#6c8ebf;

    class I,IS,IB,II income;
    class E,EH,ET,EF,EU,EE,EM,EHR,EHI,EHM,ETC,ETG,ETM,ETP,EFG,EFD,EUE,EUW,EUI,EUP,EEM,EEH,EET,EMC,EMH,EME expenses;
    class S,SE,SR,SG,SL savings;
```

This detailed breakdown provides a comprehensive view of income sources, expense categories, and savings allocations. Now, let's analyze spending trends over time.

```mermaid
gantt
    title Monthly Spending Trends
    dateFormat  X
    axisFormat %s

    section Housing
    Rent/Mortgage    :a1, 0, 1500
    Insurance        :a2, 0, 200
    Maintenance      :a3, 0, 100

    section Transportation
    Car Payment      :b1, 0, 300
    Gas              :b2, 0, 150
    Maintenance      :b3, 0, 50
    Public Transport :b4, 0, 50

    section Food
    Groceries        :c1, 0, 400
    Dining Out       :c2, 0, 200

    section Utilities
    Electricity      :d1, 0, 100
    Water            :d2, 0, 50
    Internet         :d3, 0, 70
    Phone            :d4, 0, 80

    section Entertainment
    Movies/Shows     :e1, 0, 50
    Hobbies          :e2, 0, 100
    Travel           :e3, 0, 200

    section Miscellaneous
    Clothing         :f1, 0, 100
    Healthcare       :f2, 0, 150
    Education        :f3, 0, 50
```

To provide even more insights, let's visualize savings progress towards financial goals.

```mermaid
pie showData
    title Savings Goals Progress
    "Emergency Fund" : 75
    "Retirement" : 60
    "Vacation" : 40
    "New Car" : 25
    "Home Down Payment" : 10
```

### Key Insights:

1. Housing and transportation are the largest expense categories, accounting for 45% of the monthly budget.
2. There's a good balance between essential expenses and discretionary spending, with 15% allocated to savings.
3. The emergency fund is well-funded at 75% of the goal, but long-term savings for a home down payment need attention.
4. Dining out expenses are relatively high compared to grocery spending, suggesting an area for potential savings.

### Recommendations:

1. Consider reducing dining out expenses and redirecting those funds to boost long-term savings goals.
2. Explore ways to optimize transportation costs, such as carpooling or using public transport more frequently.
3. Increase contributions to the home down payment fund to align with long-term financial goals.
4. Review and potentially negotiate utility costs to find additional savings opportunities.

This multi-layered visualization provides a comprehensive view of personal finances, from high-level budget allocation to detailed spending trends and savings progress. Users can easily identify areas for improvement and track their progress towards financial goals.

M5's adaptive complexity allows users to start with the simple pie chart for a quick overview, then dive deeper into specific areas of interest. The system can also generate personalized recommendations based on spending patterns and financial goals, providing actionable insights for better financial management.

---

### Smart Home System: Device Interactions and Energy Management

*This example demonstrates how M5 can model and visualize a complex smart home ecosystem, highlighting device interactions, automation flows, and energy management strategies. We'll create a multi-layered visualization that offers both a system-wide view and detailed insights into specific subsystems.*

**User:** Provides description of a home automation system they wish to build.

**M5:** Let's start with a high-level overview of the smart home system architecture:

```mermaid
C4Context
    title Smart Home System Architecture

    Person(user, "Homeowner", "Controls and monitors the smart home system")
    System(hub, "Central Hub", "Manages device communication and automation")
    System_Ext(cloud, "Cloud Services", "Provides remote access and data analytics")
    System_Ext(utility, "Utility Company", "Provides energy usage data and grid status")

    Boundary(home, "Smart Home") {
        System(climate, "Climate Control", "Manages heating, cooling, and air quality")
        System(security, "Security System", "Monitors and secures the home")
        System(lighting, "Lighting Control", "Manages interior and exterior lighting")
        System(appliances, "Smart Appliances", "Includes kitchen and laundry devices")
        System(energy, "Energy Management", "Monitors and optimizes energy consumption")
    }

    Rel(user, hub, "Interacts with")
    Rel(hub, cloud, "Syncs data and receives updates")
    Rel(hub, climate, "Controls")
    Rel(hub, security, "Manages")
    Rel(hub, lighting, "Adjusts")
    Rel(hub, appliances, "Coordinates")
    Rel(hub, energy, "Optimizes")
    Rel(energy, utility, "Receives data from")

    UpdateLayoutConfig($c4ShapeInRow="3", $c4BoundaryInRow="1")
```

Now, let's dive deeper into the device interactions and automation flows within the smart home system:

```mermaid
graph TB
    subgraph User Interfaces
        A[Smartphone App]
        B[Voice Assistant]
        C[Smart Display]
    end

    subgraph Central Hub
        D[Device Manager]
        E[Automation Engine]
        F[Data Analytics]
    end

    subgraph Climate Control
        G[Smart Thermostat]
        H[HVAC System]
        I[Air Quality Sensors]
    end

    subgraph Security System
        J[Smart Locks]
        K[Security Cameras]
        L[Motion Sensors]
    end

    subgraph Lighting Control
        M[Smart Bulbs]
        N[Light Switches]
        O[Occupancy Sensors]
    end

    subgraph Smart Appliances
        P[Smart Refrigerator]
        Q[Smart Oven]
        R[Smart Washer/Dryer]
    end

    subgraph Energy Management
        S[Smart Meter]
        T[Solar Panels]
        U[Battery Storage]
    end

    A --> D
    B --> D
    C --> D
    D <--> E
    D <--> F
    E --> G
    E --> J
    E --> M
    E --> P
    F --> S
    G <--> H
    G <--> I
    J <--> K
    J <--> L
    M <--> N
    M <--> O
    P <--> Q
    P <--> R
    S <--> T
    S <--> U

    classDef interface fill:#f9f,stroke:#333,stroke-width:2px;
    classDef hub fill:#ff9,stroke:#333,stroke-width:2px;
    classDef climate fill:#9cf,stroke:#333,stroke-width:2px;
    classDef security fill:#f99,stroke:#333,stroke-width:2px;
    classDef lighting fill:#9f9,stroke:#333,stroke-width:2px;
    classDef appliances fill:#f96,stroke:#333,stroke-width:2px;
    classDef energy fill:#6ff,stroke:#333,stroke-width:2px;

    class A,B,C interface;
    class D,E,F hub;
    class G,H,I climate;
    class J,K,L security;
    class M,N,O lighting;
    class P,Q,R appliances;
    class S,T,U energy;
```

To provide insights into energy management, let's visualize energy consumption patterns and optimization strategies:

```mermaid
gantt
    title Daily Energy Consumption and Optimization
    dateFormat HH:mm
    axisFormat %H:%M

    section HVAC
    Reduced Usage (Night)     :a1, 00:00, 6h
    Optimal Start (Morning)   :a2, 06:00, 2h
    Eco Mode (Day)            :a3, 08:00, 10h
    Peak Shaving (Evening)    :a4, 18:00, 4h
    Setback (Night)           :a5, 22:00, 2h

    section Lighting
    Outdoor Off               :b1, 00:00, 5h
    Adaptive Indoor           :b2, 05:00, 19h
    Outdoor On                :b3, 19:00, 5h

    section Appliances
    Standby Mode              :c1, 00:00, 6h
    Smart Scheduling          :c2, 06:00, 14h
    Energy-Intensive Tasks    :c3, 20:00, 4h

    section Solar Generation
    No Generation             :d1, 00:00, 6h
    Increasing Generation     :d2, 06:00, 6h
    Peak Generation           :d3, 12:00, 6h
    Decreasing Generation     :d4, 18:00, 4h
    No Generation             :d5, 22:00, 2h

    section Battery Storage
    Charging                  :e1, 00:00, 12h
    Peak Shaving Support      :e2, 12:00, 10h
    Idle                      :e3, 22:00, 2h
```

Now, let's visualize the real-time energy flow within the smart home system:

```mermaid
sankey-beta
    Solar Panels,Battery Storage,2
    Solar Panels,Home Consumption,5
    Solar Panels,Grid Export,3
    Grid Import,Home Consumption,4
    Battery Storage,Home Consumption,1
    Home Consumption,HVAC,4
    Home Consumption,Lighting,2
    Home Consumption,Appliances,3
    Home Consumption,Other Devices,1
```

### Key Insights:

1. The smart home system integrates multiple subsystems (climate, security, lighting, appliances, and energy) under a central hub, allowing for coordinated control and optimization.
2. Device interactions are complex, with the automation engine playing a crucial role in orchestrating actions based on user preferences, sensor data, and energy considerations.
3. Energy consumption is carefully managed throughout the day, with strategies like optimal start for HVAC, adaptive lighting, and smart scheduling of appliances.
4. Solar generation and battery storage are leveraged to reduce grid dependence, with excess energy exported to the grid during peak generation hours.
5. Real-time energy flow visualization shows that the home is currently net-positive, exporting more energy to the grid than it's importing.

### Recommendations:

1. Implement predictive HVAC control based on weather forecasts and historical usage patterns to further optimize energy consumption.
2. Enhance appliance scheduling to take advantage of peak solar generation hours, reducing reliance on grid power.
3. Explore opportunities for demand response programs with the utility company, using the battery storage system to support grid stability during peak hours.
4. Consider expanding the solar panel system or increasing battery capacity to further reduce grid dependence and potentially achieve full energy self-sufficiency.

This multi-layered visualization provides a comprehensive view of a smart home system, from high-level architecture to detailed device interactions and energy management strategies. Users can easily understand how different components work together and identify opportunities for further optimization.

M5's adaptive complexity allows users to start with the system architecture for a broad overview, then dive deeper into specific subsystems or energy flows based on their interests or troubleshooting needs. The system can also generate real-time insights and recommendations based on current device status, energy consumption patterns, and external factors like weather or utility pricing.

---

### Fitness Journey: Workout Routine and Progress Tracking

*This example demonstrates how M5 can help users plan, track, and optimize their fitness journey. We'll create a multi-layered visualization that offers both a high-level view of the fitness program and detailed insights into workouts and progress.*

**User:** Provides details on their fitness plan, and stats.

**M5:** Let's start with an overview of the fitness program structure:

```mermaid
mindmap
    root((Fitness Journey))
        Goal Setting
            Weight Loss
            Muscle Gain
            Endurance Improvement
            Flexibility Enhancement
        Workout Planning
            Strength Training
                Upper Body
                Lower Body
                Core
            Cardio
                HIIT
                Steady State
            Flexibility
                Yoga
                Stretching
        Nutrition
            Meal Planning
            Macronutrient Tracking
            Hydration
        Progress Tracking
            Body Measurements
            Performance Metrics
            Progress Photos
        Recovery
            Rest Days
            Sleep Optimization
            Injury Prevention
```

Now, let's dive into a detailed weekly workout routine:

```mermaid
gantt
    title Weekly Workout Routine
    dateFormat  YYYY-MM-DD
    axisFormat %a
    
    section Strength Training
    Upper Body     :active, 2023-05-01, 1d
    Lower Body     :active, 2023-05-03, 1d
    Full Body      :active, 2023-05-05, 1d
    
    section Cardio
    HIIT           :active, 2023-05-02, 1d
    Steady State   :active, 2023-05-04, 1d
    
    section Flexibility
    Yoga           :active, 2023-05-06, 1d
    
    section Rest
    Rest Day       :crit, 2023-05-07, 1d
```

Let's break down a specific workout session, focusing on the upper body strength training day:

```mermaid
graph TD
    A[Upper Body Workout] --> B[Warm-up]
    A --> C[Main Exercises]
    A --> D[Cool-down]
    
    B --> B1[5 min cardio]
    B --> B2[Dynamic stretching]
    
    C --> C1[Bench Press]
    C --> C2[Rows]
    C --> C3[Shoulder Press]
    C --> C4[Pull-ups]
    C --> C5[Bicep Curls]
    C --> C6[Tricep Extensions]
    
    C1 --> C1a[3 sets x 8-10 reps]
    C2 --> C2a[3 sets x 8-10 reps]
    C3 --> C3a[3 sets x 8-10 reps]
    C4 --> C4a[3 sets x max reps]
    C5 --> C5a[3 sets x 12-15 reps]
    C6 --> C6a[3 sets x 12-15 reps]
    
    D --> D1[Static stretching]
    D --> D2[Foam rolling]

    classDef warmup fill:#f9f,stroke:#333,stroke-width:2px;
    classDef main fill:#bbf,stroke:#333,stroke-width:2px;
    classDef cooldown fill:#bfb,stroke:#333,stroke-width:2px;

    class B,B1,B2 warmup;
    class C,C1,C2,C3,C4,C5,C6,C1a,C2a,C3a,C4a,C5a,C6a main;
    class D,D1,D2 cooldown;
```

### Key Insights:

1. The fitness program is well-rounded, incorporating strength training, cardio, and flexibility work throughout the week.
2. The upper body workout is structured with a proper warm-up, a balanced selection of exercises targeting all major muscle groups, and a cool-down routine.
3. Over the 12-week period, there's a clear trend of decreasing body weight, increasing strength (as measured by bench press 1RM), and improving endurance (5K run time).
4. Body composition analysis shows a healthy distribution of muscle mass, fat mass, bone mass, and water, indicating effective body recomposition.

### Recommendations:

1. Consider periodization in the workout routine to prevent plateaus and optimize long-term progress.
2. Implement progressive overload by gradually increasing weights or reps in strength training exercises.
3. Vary cardio intensities and durations to continue challenging the cardiovascular system and improving endurance.
4. Monitor recovery closely, especially as workout intensity increases, to prevent overtraining and reduce injury risk.
5. Adjust nutrition plan based on changing body composition and performance goals.

This multi-layered visualization provides a comprehensive view of a fitness journey, from high-level program structure to detailed workout plans and progress tracking. Users can easily understand their fitness routine, track their progress, and identify areas for improvement.

M5's adaptive complexity allows users to start with the fitness program overview for a broad perspective, then dive deeper into specific workouts, exercises, or progress metrics based on their current focus or goals. The system can also generate personalized recommendations based on progress data, recovery status, and individual goals.

---

## Contributing

You are welcome to contribute to the development of M5. Please join the discord or contact Devin Pellegrino to speak more.

## License

M5 Custom License

Copyright (c) 2024 Devin Pellegrino

Permission is hereby granted, free of charge, to any individual for personal, non-commercial use of this software and associated documentation files (the "Software"), including the rights to use, copy, modify, and adapt the Software, subject to the following conditions:

1. The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

2. You may not use the Software for any commercial or business purposes without explicit written permission from Devin Pellegrino. For business use inquiries, please contact at devin@nerority.com.

3. You may not distribute, sublicense, or sell copies of the Software without explicit written permission from Devin Pellegrino.

4. Any adaptations or modifications of the Software must be clearly marked as such, and you may not attempt to claim any part of the original work as your own.

5. Attribution to Devin Pellegrino as the original author of M5 must be included in any use, adaptation, or derivative work of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHOR OR COPYRIGHT HOLDER BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.

---

## Contact

- **Creator:** Devin Pellegrino (Nerority)
- **Email:** devin@nerority.com
- **Website:** [Nerority Insiders](https://nerority.webflow.io/public/home)

---

<p align="center">
  <i>Unleash the power of hyperspace visualization with M5!</i>
</p>
