# Objective of 4 bit carry lookahead adder:

It computes the carries parallely thus greatly speeding up the computation.

1. understanding behaviour of carry lookahead adder from module designed by the student as part of the experiment
2. understanding the concept of reducing computation time with respect of ripple carry adder by using carry generate and propagate functions
3. the adder wil add two 4 bit numbers

#### Examining behaviour of carry lookahead adder for the module designed by the student as part of the experiment (refer to the circuit diagram)

#### Loading data in the carry lookahead adder (refer to procedure tab for further detail and experiment manual for pin numbers)
- load the two input numbers in the adder units as:
  - 1111 and 0001

#### Examining the carry generate and propagate function behaviour:
- check output sum 0000
- check final output carry 1
- check intermediate carry bit and sum bit of the unit adders and verify the values of carry generate and propagate function (refer to theory)
- probing the any port can be done by verifying the color of the wire coming out of the port

#### Recommended learning activities for the experiment: 
Leaning activities are designed in two stages, a basic stage and an advanced stage. Accomplishment of each stage can be self-evaluated through the given set of quiz questions consisting of multiple type and subjective type questions. In the basic stage, it is recommended to perform the experiment firstly, on the given encapsulated working module, secondly, on the module designed by the student, having gone through the theory, objective and procuder. By performing the experiment on the working module, students can only observe the input-output behavior. Where as, performing experiments on the designed module, students can do circuit analysis, error analysis in addition with the input-output behavior. It is recommended to perform the experiments following the given guideline to check behavior and test plans along with their own circuit analysis. Then students are recommended to move on to the advanced stage. The advanced stage includes the accomplishment of the given assignments which will provide deeper understanding of the topic with innovative circuit design experience. At any time, students can mature their knowledge base by further reading the references provided for the experiment.

- color configuration of wire for 5 valued logic supported by the simulator:
  - if value is UNKNOWN, wire color= maroon
  - if value is TRUE, wire color= blue
  - if value is FALSE, wire color= black
  - if value is HI IMPEDENCE, wire color= green
  - if value is INVALID, wire color= orange

# Test plan:
1. Set one input to zero(0) and check the output.
2. Set one input to all one and another as 0001 in carry lookahead adder.
3. Check the carry lookahead adder with two arbritrary input. Check the output and show the carry propagator and generator output for every bit.

Use Display units for checking output. Try to use minimum number of components to build. The pin configuration of the canned components are shown when mouse hovered over a component.

# Assignment Statements :
1. Design a 4-bit carry lookahead adder circuit using half adders and full adders and test it by giving proper input.
2. Design a 16-bit carry lookahead adder circuit using half adders and full adders and test it by giving proper input.