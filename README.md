# Learning-SCL
Learning Siemens SCL Language for Automation.

Software: TIA Portal v17

```Calculate

//幂运算 Power
"Calculate_DB".Power.Int_c := "Calculate_DB".Power.Int_b ** "Calculate_DB".Power.Int_a;

//加法运算 ADD
"Calculate_DB".ADD.Int_c := "Calculate_DB".ADD.Int_b + "Calculate_DB".ADD.Int_a;

//减法运算 SUB
"Calculate_DB".SUB.Int_c := "Calculate_DB".SUB.Int_b - "Calculate_DB".SUB.Int_a;

//乘法运算 MUL
"Calculate_DB".MUL.Int_c := "Calculate_DB".MUL.Int_b * "Calculate_DB".MUL.Int_a;

//除法运算 DIV
"Calculate_DB"."DIV".Int_c := "Calculate_DB"."DIV".Int_b / "Calculate_DB"."DIV".Int_a;

//计算 a+(b*c) 在进行幂运算 **2 再 /4 Calculate
"Calculate_DB".Calculate.Int_d_Output := (("Calculate_DB".Calculate.Int_c_Input * "Calculate_DB".Calculate.Int_b_Input) + "Calculate_DB".Calculate.Int_a_Input) ** 2 / 4;

```
