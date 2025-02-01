DIGITAL FILTER DESIGN
COMPANY NAME : CODTECH IT SOLUTION
NAME : Piyush Sharma
INTERN ID : CT08IPC
DOMAIN : VLSI
BATCH DURATION : January 5th, 2025 to February 5th, 2025
MENTOR NAME : NEELA SANTOSH Kumar

Description: 
1. Objective:
DESIGN AND SIMULATE A DIGITAL FIR (FINITE IMPULSE RESPONSE)
FILTER USING VERILOG. The FIR filter is designed using a systematic and modular approach, incorporating key components that contribute to its efficiency and functionality. One of the essential elements is the Filter Coefficients, which are predefined constants that determine the filter’s impulse response. These coefficients dictate how each input sample influences the final output, ensuring proper signal shaping and controlled signal modification.

Another crucial component is the Delay Line, which consists of a shift register that stores past input values required for convolution-based filtering. This mechanism allows the filter to operate over multiple input samples, enhancing signal accuracy by considering historical data in its computations. By retaining past samples, the delay line ensures smooth and stable filtering behavior.

The Weighted Summation serves as the core of the FIR filter operation. In this process, past input samples are multiplied by their corresponding filter coefficients and summed together to produce the final filtered output. This summation effectively removes unwanted noise while amplifying or preserving desired signal components, making the FIR filter highly suitable for applications in noise reduction, signal smoothing, and feature extraction.

2. Verilog Implementation:
   Key components include:
   Filter Coefficients (coeff): Preloaded constants representing the
   • FIR filter's impulse response.
    • Delay Line (delay_line): A shift register to store past input samples.
    • Weighted Summation (y_out): Computes the filtered output by multiplying the coefficients and delay line values.

![image](https://github.com/user-attachments/assets/3bbe51ec-77ed-40fe-ac43-d674b4edb67b)

3. Simulation:
   The simulation verified the following: 
    1.	Reset Behavior: The filter output (y_out) initializes to 0 when the reset signal (rst) is asserted. 
    2.	Filtering Behavior: For a step input signal:  The output reflects the weighted sum of the most recent inputs, scaled         by the filter coefficients. o Matches expected theoretical output.
   ![image](https://github.com/user-attachments/assets/0630f49c-5310-4330-9bdb-6f0c738e5e43)

