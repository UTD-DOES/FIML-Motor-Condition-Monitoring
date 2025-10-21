# FIML-Motor-Condition-Monitoring
The cascading non-intrusive cascading FFT-informed machine learning (FIML) framework is able to detect both electrical and mechanical faults in squirrel-cage induction motors. Experimented by FM Research, four IM faults are analyzed: short-circuit faults, broken rotor bars (BRBs), and mechanical unbalance (MU). Using high-resolution signals, fault-related frequency components can be extracted through fast Fourier transform (FFT) analysis. The proposed FFT-informed machine learning (FIML) framework inputs fault-related frequency components into machine learning models. Besides, a cascading workflow is proposed for accurately detecting and diagnosing electrical and mechanical faults (Figure 1). Three machine learning (ML) algorithms are studied to verify the proposed FIML framework: long short-term memory (LSTM), gated recurrent unit (GRU), and two-dimensional convolutional neural networks (2D CNN).


<p align="center">
  <img width="330.9" height="284.85" src="https://github.com/user-attachments/assets/bc6283aa-3b00-405b-9dd9-140fb82c10bc" />
</p>

<p align="center">
    <em> Figure 1: FFT-informed machine learning Workflow </em>
</p>
