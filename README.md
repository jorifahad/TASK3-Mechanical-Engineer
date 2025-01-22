### Torque Calculation for Robotic Arm (Updated)

#### Given Data:
1. **Arm Lengths:**
   - First arm: \( 15 cm \) (\( 0.15 m )).
   - Second arm: \( 10 cm\) (\( 0.10 m)).
   - Third arm: \( 4 cm \) (\( 0.04 m )).

2. **Hanging Weight:** \( 1 kg).
3. **Gravitational Acceleration:** \( g = 9.81 m/s^2 ).

---

### Step 1: Calculate the Force \( F \)
The force acting due to the hanging weight is calculated as:

![image](https://github.com/user-attachments/assets/4104dc84-2efc-4445-858c-ede3628032c2)


---

### Step 2: Calculate the Torque for Each Joint
The torque at each joint depends on the distance \( r \) from the pivot point and the load acting on it.

#### 1. Joint 1 (Base):
This joint supports the entire arm (the weight of the hanging object plus the arms).  
The torque at the first joint is:

![image](https://github.com/user-attachments/assets/88c92675-922e-47bf-a191-be4cbe70d287)

Substituting the arm lengths:

![image](https://github.com/user-attachments/assets/cfecae7a-eb06-49db-966e-65830765b77b)


---

#### 2. Joint 2 (Middle):
This joint supports the weight of the arms beyond it (second and third arms) plus the hanging weight.  
The torque at the second joint is:

![image](https://github.com/user-attachments/assets/d60d8357-f0ef-4b55-a58b-c483d80f86d8)

Substituting the arm lengths:

![image](https://github.com/user-attachments/assets/e7ad5682-7dbe-4acc-8138-a7d286fe2ddf)

---

#### 3. Joint 3 (End-Effector):
This joint supports only the weight of the hanging object.  
The torque at the third joint is:

![image](https://github.com/user-attachments/assets/b3b9ac2d-70e3-4976-b411-75e945882d89)

Substituting the arm length:

![image](https://github.com/user-attachments/assets/3ca86ec7-eea5-494f-bc54-a85a86d367a1)


---

### Step 3: Motor Selection
Based on the calculated torques, the following motors are recommended:

1. **For Joint 1 (Base):** Select a motor with a torque rating greater than \( 2.845 Nm \).
2. **For Joint 2 (Middle):** Select a motor with a torque rating greater than \( 1.375 Nm \).
3. **For Joint 3 (End-Effector):** Select a motor with a torque rating greater than \( 0.392 Nm \).

---

### Suggested Servo Motors:
- **For Joint 3:** Consider the **MG996R Servo Motor**, which offers a torque of approximately

 ![image](https://github.com/user-attachments/assets/e0bd561f-2cd2-464d-8dab-8e2d81910bd3)

- **For Joints 1 and 2:** Choose higher-torque motors based on the calculated requirements.

---

### Purchase Links:
- [MG996R Servo Motor on Amazon](https://www.amazon.com/s?k=MG996R)
- [High Torque Servo Motors on Amazon](https://www.amazon.com/s?k=high+torque+servo+motor)
