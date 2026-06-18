# 📊 Experimental Archetype Matrix (Core Spectrum Profile)

An experimental, client-side architectural profile application that maps behavioral metrics across dual-pole cognitive, emotional, and social axes, alongside an absolute unipolar energy scale. 

This matrix clusters related traits inspired by structural personality inventory models to generate **16 distinct behavioral profiles**.

---

## 🧭 The Core Spectrum Axes

The system calculates individual profiles by mapping answers across four distinct architectural systems:

### 1. Cognitive Regulation Axis (`O` vs `A`)
Maps how an individual processes structure, predictability, and incoming stimuli.
*   **Pole Left (OCD Style - `O`):** Driven by structural precision, symmetry, checking routines, and rigid frameworks to mitigate situational anxiety.
*   **Pole Right (ADHD Style - `A`):** Characterized by high novelty-seeking, focus fragmentation, organic impulse navigation, and flexible time boundaries.

### 2. Emotional Reactivity Axis (`H` vs `P`)
Measures baseline autonomic nervous system arousal and response to external tension.
*   **Pole Left (Histrionic/Neurotic Style - `H`):** Rapid emotional amplification, intense sensitivity to social or interpersonal feedback, and expressive orientation.
*   **Pole Right (Psychopathic Style - `P`):** High psychological detachment under crisis, low baseline fear responses, and flat natural emotional empathy.

### 3. Social Architecture Axis (`A` vs `N`)
Defines the structure of the ego in relation to social networks and communication.
*   **Pole Left (Autistic Style - `A`):** Reliance on immutable routines, systemizing incoming data inputs, and direct, implicit-cue-free communication.
*   **Pole Right (Narcissistic Style - `N`):** An expansive, agentic ego structure driven by status-striving, high self-validation, and an appetite for systemic recognition.

### 4. Pervasive Energy Scale (`S` vs `D`)
*Calculated as a clean unipolar burden progression from 0% to 100%.*
*   **0% Baseline (Standard Vitality - `S`):** An active, unencumbered energetic baseline capable of standard daily operational maintenance and future-oriented goal-striving.
*   **100% Baseline (Depressive Burden - `D`):** Systemic energy depletion, flattened emotional capacity, high execution friction, and structural pessimism.

---

## 📈 Metric & Weight Tracking Formulas

### Absolute OCD Style Weight
While the **Cognitive Regulation Axis** determines whether you lean overall toward an **O** or **A** classification, the app calculates an absolute, localized weight for the `O` spectrum using the following bounds:

$$\text{OCD Style Weight (\%)} = 100 - \left( \frac{\text{Current Score} - \text{Min Possible Score}}{\text{Max Possible Score} - \text{Min Possible Score}} \times 100 \right)$$

This isolates your explicit structural-control burden regardless of fluctuating ADHD traits.

### Unipolar Depressive Burden
Unlike traditional bipolar scales, the **Pervasive Energy Scale** maps data strictly from a zero-point baseline ($-\text{Max}$) up to a maximized burden state ($+\text{Max}$), visualizing fatigue as an additive weight rather than a directional balance:

$$\text{Depressive Burden (\%)} = \frac{\text{Current Score} - \text{Min Possible Score}}{\text{Max Possible Score} - \text{Min Possible Score}} \times 100$$

---

## 🗃️ The 16 Matrix Archetype Profiles

| Code | Archetype Name | Structural Focus |
| :--- | :--- | :--- |
| **OHAS** | The Perfectionist Safe-Keeper | Highly organized, emotionally acute, system-driven, resilient operational energy. |
| **OHAD** | The Isolated Sentinel | High cognitive self-policing, highly sensitive, low baseline energetic fuel. |
| **OHNS** | The Dramatic Orchestrator | Demands order, highly expressive, attention/status-focused, high energy loop. |
| **OHND** | The Fragile Sovereign | High aspirations/pride, acute sensitivity to slight, low physical momentum. |
| **OPAS** | The Systemizing Engineer | Rational order-seeking, highly detached under pressure, systematic logic lanes. |
| **OPAD** | The Detached Analyst | Deep logical isolation, cold unbothered stance, highly compressed energy supply. |
| **OPNS** | The Strategic Director | Highly organized, fearless under stress, ambitious executive network controller. |
| **OPND** | The Cold Architect | High authority mindset, calculating calm, operates behind the scenes via low fuel. |
| **AHAS** | The Creative Storm | High fluidity, novelty-seeking, passionate emotional depth, active curiosity. |
| **AHAD** | The Wandering Romantic | Shifting thoughts, deep emotional resonance, low active output, introspective. |
| **AHNS** | The Charismatic Maverick | Rejects rigid rules, highly adaptive, status-driven, high energy improviser. |
| **AHND** | The Volatile Free-Agent | Unpredictable focus, easily stung by setbacks, ambitious but physically exhausted. |
| **APAS** | The Independent Explorer | Spontaneous focus, unshakeable crisis calm, direct literal communication style. |
| **APAD** | The Ghost Observer | Unstructured detachment, low demand lifestyle, quiet observer of ecosystems. |
| **APNS** | The Opportunistic Pioneer | Fluid target-spotter, absolute fearlessness, high energy, leverages immediate openings. |
| **APND** | The Drifting Outlaw | Rejects authority/routines, unbothered by social pressure, conserves low energy. |

---

## 🛠️ Architecture & Setup

This repository contains a lightweight, zero-dependency, single-file HTML5 interface powered by vanilla CSS custom properties and asynchronous JavaScript render loops.

1. Clone the repository: `git clone https://github.com/yourusername/core-spectrum-matrix.git`
2. Open `index.html` in any modern web browser.
3. No build tools, compilation steps, or backend server nodes required.

⚠️ *Disclaimer: This matrix is an experimental behavioral mapping exercise. It does not provide clinical evaluations, psychological assessments, or psychiatric diagnostic criteria.*
