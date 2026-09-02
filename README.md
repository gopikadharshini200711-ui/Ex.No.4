# Ex.No.4-EXP 4 Generate the Prompt and evaluate that for following prompt patterns - Zero-shot Prompting.• Few-shot Prompting - Chain of Thought - Persona Pattern - Reverse Prompting - Graph Prompting - Active Prompting

### DATE: 02.09.2026

### REGISTER NUMBER : 212225230083

### Aim: To write the prompt for the following prompt types and compare that with different AI tools and evaluate that using any one evaluation method (Ex. Rubrics). Zero-shot Prompting.• Few-shot Prompting - Chain of Thought - Persona Pattern - Reverse Prompting - Graph Prompting - Active Prompting

# Use Case :

## Smart Manufacturing Automation using IoT and Embedded Controllers

### Scenario

The manufacturing industry is looking to reduce manual monitoring and increase efficiency through automation. IoT devices and embedded controllers are used to automate equipment, monitor performance in real time, and enable predictive maintenance. The goal is to streamline production, minimize downtime, and enhance energy efficiency.

### Target Audience

- Manufacturing companies (automotive, electronics, food processing)
- Industrial automation engineers
- Plant maintenance teams
- IoT system developers
- Production managers

### Main Objectives

- Improve production efficiency by 30%.
- Minimize machinery downtime with predictive maintenance.
- Enable real-time monitoring and remote control of manufacturing systems.
- Reduce energy consumption by optimizing processes.

---

# Prompt Design and Evaluation

## 1. Zero-shot Prompting

### Prompt
> Explain how IoT and embedded controllers can be used to enable predictive maintenance in a manufacturing plant.

### Expected AI Response

IoT sensors attached to machinery collect real-time data such as vibration, temperature, and pressure. Embedded controllers process this data locally and transmit it to a central system, where algorithms detect early warning signs of failure. This allows maintenance to be scheduled proactively, reducing unplanned downtime.

### Observation

The model generates a complete response without being provided with any examples.

---

## 2. Few-shot Prompting

### Prompt

**Example 1**

**Input:** Vibration levels exceed normal range on Machine A.
**Output:** Flag Machine A for inspection and schedule maintenance within 24 hours.

**Example 2**

**Input:** Motor temperature rises above safe threshold.
**Output:** Automatically reduce load and alert the maintenance team.

**Now Answer**

**Input:** Sudden pressure drop detected in the hydraulic system.

### Expected AI Response

Trigger an immediate alert to the maintenance team, temporarily reduce system load to prevent damage, and schedule an urgent inspection of the hydraulic system.

### Observation

Providing examples helps the AI understand the expected response format and improves consistency.

---

## 3. Chain of Thought Prompting

### Prompt
> A manufacturing plant wants to reduce equipment downtime using IoT. Think step by step: identify data to collect, explain how it is transmitted, explain how failures are predicted, describe the maintenance action taken, and summarize the benefit.

### Expected AI Response

1. Sensors collect data such as temperature, vibration, and pressure from machines.
2. Embedded controllers transmit this data in real time to a central monitoring system via IoT networks.
3. Machine learning models analyze the data for abnormal patterns indicating potential failure.
4. When risk is detected, the system alerts maintenance staff to service the specific machine before failure occurs.
5. This reduces unplanned downtime, lowers repair costs, and improves overall production efficiency.

### Observation

The response follows a logical sequence, making the reasoning process easier to understand.

---

## 4. Persona Pattern

### Prompt
> You are an experienced IoT systems engineer at a manufacturing plant. Explain to plant management how predictive maintenance will benefit operations.

### Expected AI Response

As your IoT systems engineer, our new predictive maintenance setup uses sensors on critical machines to monitor performance continuously. Instead of following a fixed maintenance schedule or waiting for breakdowns, we service equipment exactly when needed. This cuts unplanned downtime, reduces maintenance costs, and helps us reach our efficiency targets.

### Observation

The response reflects the perspective and expertise of an industrial automation professional.

---

## 5. Reverse Prompting

### Prompt
> A manufacturing plant reduced downtime by 40%, cut energy costs, and avoided three major equipment failures using an automated monitoring system. What prompt could have generated this outcome?

### Expected AI Response

Design an IoT-based predictive maintenance and energy optimization system for a manufacturing plant that monitors equipment health in real time, predicts failures before they occur, and automatically adjusts operations to reduce energy consumption.

### Observation

The AI infers the original prompt from the desired output.

---

## 6. Graph Prompting

### Prompt
> Represent the workflow of an IoT-based predictive maintenance system as a flow diagram.

### Expected AI Response

```
Start
   ↓
Sensor Data Collection
   ↓
Data Transmission (Embedded Controllers)
   ↓
Analysis & Failure Prediction
   ↓
Alert Generation
   ↓
Maintenance Action
   ↓
Reduced Downtime
   ↓
Process Complete
```

### Observation

Graph prompting organizes the information visually, making workflows easier to understand.

---

## 7. Active Prompting

### Prompt
> Analyze whether a machine showing early vibration warnings should be shut down immediately. If additional information is required, ask follow-up questions before giving the final recommendation.

### Expected AI Response

The AI first asks questions such as:

- How severe is the vibration compared to the safety threshold?
- Is the machine part of a critical production line?
- Is a replacement or backup machine available?
- How long until the next scheduled maintenance window?

After receiving the information, it recommends either continuing operation with close monitoring or shutting down for immediate inspection based on the risk level.

### Observation

The AI actively gathers missing information before making a decision, improving accuracy.

---

# Outputs for Each Prompting Technique

## 1. Zero-shot Prompting

### Prompt

Explain how IoT and embedded controllers can be used to enable predictive maintenance in a manufacturing plant.

### AI Output

IoT sensors mounted on machinery continuously capture parameters such as temperature, vibration, and pressure. Embedded controllers process this data at the edge and relay it to a centralized monitoring system. Predictive algorithms analyze the incoming data streams to identify early signs of wear or malfunction, enabling maintenance teams to intervene before a failure occurs, thereby minimizing unplanned downtime and extending equipment lifespan.

---

## 2. Few-shot Prompting

### Prompt

Example 1

Input: Vibration levels exceed normal range on Machine A.

Output: Flag Machine A for inspection and schedule maintenance within 24 hours.

Example 2

Input: Motor temperature rises above safe threshold.

Output: Automatically reduce load and alert the maintenance team.

Now answer:

Input: Sudden pressure drop detected in the hydraulic system.

### AI Output

Output: Immediately alert the maintenance team, reduce system load to prevent further stress, and schedule an urgent inspection of the hydraulic system to identify the cause of the pressure drop.

---

## 3. Chain of Thought Prompting

### Prompt

A manufacturing plant wants to reduce equipment downtime using IoT. Explain step by step how the process works.

### AI Output

Step 1: Sensors on machines continuously collect operational data (temperature, vibration, pressure).

Step 2: Embedded controllers transmit this data in real time to a central or cloud-based monitoring system.

Step 3: AI algorithms analyze the data to detect deviations from normal operating patterns.

Step 4: When a potential failure is predicted, the system generates an alert for the maintenance team.

Step 5: Maintenance is scheduled proactively for the specific machine, avoiding unplanned stoppages.

Step 6: Historical data is used to continuously refine failure-prediction accuracy over time.

Step 7: The plant benefits from lower downtime, reduced repair costs, and improved overall efficiency.

---

## 4. Persona Pattern

### Prompt

You are an experienced IoT systems engineer at a manufacturing plant. Explain to plant management how predictive maintenance will benefit operations.

### AI Output

As your IoT systems engineer, I want to highlight that our predictive maintenance setup uses sensors on critical machines to monitor real-time performance. Rather than relying on fixed schedules or reacting after a breakdown, we can now service equipment exactly when it's needed. This approach significantly reduces unplanned downtime, lowers maintenance costs, and helps us meet our production efficiency targets while keeping the plant running smoothly.

---

## 5. Reverse Prompting

### Prompt

A manufacturing plant reduced downtime by 40%, cut energy costs, and avoided three major equipment failures using an automated monitoring system. Generate the prompt that could have produced this outcome.

### AI Output

Design an IoT-based predictive maintenance and energy optimization system for a manufacturing plant that continuously monitors equipment health, predicts failures before they occur, automatically adjusts operational parameters to save energy, and minimizes unplanned downtime across the production line.

---

## 6. Graph Prompting

### Prompt

Represent the workflow of an IoT-based predictive maintenance system as a flow diagram.

### AI Output

```
Start
   │
   ▼
Sensor Data Collection
   │
   ▼
Data Transmission (Embedded Controllers)
   │
   ▼
Data Analysis & Anomaly Detection
   │
   ▼
Failure Prediction
   │
   ▼
Alert Generation
   │
   ▼
Maintenance Action Scheduled
   │
   ▼
Reduced Downtime & Energy Savings
   │
   ▼
Process Complete
```

---

## 7. Active Prompting

### Prompt

Analyze whether a machine showing early vibration warnings should be shut down immediately. Ask for any missing information before making a recommendation.

### AI Output

Before making a decision, I need the following information:

1. How severe is the vibration compared to the safety threshold?
2. Is this machine part of a critical production line?
3. Is a backup or replacement machine available?
4. How long until the next scheduled maintenance window?
5. What is the estimated cost of an unplanned failure versus a planned shutdown?

Based on the answers:

- If vibration is within a moderate range and a backup is available, continue operation under close monitoring.
- If vibration is severe or no backup exists, shut down immediately for inspection to prevent a costly failure.

---

# Comparison with Different AI Tools

| Prompt Type         | ChatGPT                            | Google Gemini        | Microsoft Copilot   |
| -------------------- | ----------------------------------- | ---------------------- | ---------------------- |
| Zero-shot Prompting  | Detailed and accurate               | Clear explanation      | Moderate detail        |
| Few-shot Prompting   | Learns examples effectively         | Good consistency       | Adequate                |
| Chain of Thought     | Well-structured reasoning           | Logical explanation    | Basic reasoning         |
| Persona Pattern      | Natural expert response             | Professional style     | Brief                   |
| Reverse Prompting    | Highly accurate prompt generation   | Good                   | Moderate                |
| Graph Prompting      | Clear workflow representation       | Good flow               | Simple diagram          |
| Active Prompting     | Excellent follow-up questioning     | Good clarification     | Limited questions       |

---

# Evaluation Method – Rubrics

## Evaluation Criteria

| Criteria    | Excellent (5)          | Good (4)        | Average (3)        |
| ----------- | ----------------------- | ----------------- | --------------------- |
| Reasoning   | Logical and complete     | Mostly logical    | Basic reasoning       |
| Correctness | Highly accurate          | Minor errors      | Some inaccuracies     |
| Token Usage | Efficient and concise    | Moderate          | Slightly verbose       |

---

## Rubrics Scores

| AI Tool            | Reasoning | Correctness | Token Usage | Total / 15 |
| -------------------- | ----------- | ------------- | -------------- | ------------ |
| ChatGPT             | 5         | 5           | 5            | **15**       |
| Google Gemini       | 4         | 5           | 4            | **13**       |
| Microsoft Copilot   | 4         | 4           | 4            | **12**       |

---

# Result Analysis

- **ChatGPT** generated the most logical, accurate, and concise responses across all prompting techniques.
- **Google Gemini** produced technically correct responses with good reasoning but occasionally used more tokens.
- **Microsoft Copilot** provided shorter responses suitable for quick understanding but with less detailed reasoning.

---

# Conclusion

This experiment successfully demonstrated the use of advanced prompting techniques for an IoT-based Smart Manufacturing predictive maintenance system. Zero-shot prompting generated responses without examples, few-shot prompting improved consistency using sample inputs, chain-of-thought prompting enhanced logical reasoning, persona prompting produced expert-level explanations, reverse prompting inferred the original query from the output, graph prompting presented the workflow visually, and active prompting improved decision-making through follow-up questions. Based on the evaluation using reasoning, correctness, and token usage, ChatGPT achieved the highest overall score due to its clear reasoning, high accuracy, and efficient response generation.

---

# Result

Thus, the advanced prompting techniques were implemented successfully, compared across different AI tools, and evaluated using a rubric-based method. The Smart Manufacturing predictive maintenance case study demonstrated that selecting the appropriate prompting technique significantly improves AI reasoning, correctness, and response efficiency for industrial automation applications. Thus, the experiment successfully achieved its objective of understanding and evaluating advanced prompt engineering techniques for real-world engineering scenarios.
