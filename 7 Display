int num = 0; 
int b1 = 0; 
int b2 = 0; 

void setup() {                 
  pinMode(2, INPUT); 
  pinMode(3, INPUT); 
  pinMode(4, OUTPUT); 
  pinMode(5, OUTPUT); 
  pinMode(6, OUTPUT); 
  pinMode(7, OUTPUT); 
  pinMode(8, OUTPUT); 
  pinMode(9, OUTPUT); 
  pinMode(10, OUTPUT); 
  pinMode(11, OUTPUT);   
} 

void loop() { 
  b1 = digitalRead(2); 
  b2 = digitalRead(3); 
  
  if (b1 == LOW && num <= 9) { 
    num++; 
  } if (b2 == LOW && num >= 0) { 
    num--; 
  } 
  
  switch (num) { 
    case 0: 
      reset();  
    digitalWrite(10,HIGH); 
    digitalWrite(5,HIGH); 
    digitalWrite(6,HIGH); 
    digitalWrite(7,HIGH); 
    digitalWrite(8,HIGH); 
    digitalWrite(9,HIGH);    
      break; 
    case 1: 
      reset();  
    digitalWrite(8,HIGH); 
    digitalWrite(5,HIGH);  
      break; 
    case 2: 
      reset();  
    digitalWrite(9,HIGH); 
    digitalWrite(8,HIGH); 
    digitalWrite(6,HIGH); 
    digitalWrite(7,HIGH); 
    digitalWrite(11,HIGH);  
      break; 
    case 3: 
      reset(); 
    digitalWrite(11,HIGH); 
    digitalWrite(5,HIGH); 
    digitalWrite(7,HIGH); 
    digitalWrite(8,HIGH); 
    digitalWrite(9,HIGH);  
      break; 
    case 4: 
      reset();  
    digitalWrite(8,HIGH); 
    digitalWrite(5,HIGH); 
    digitalWrite(10,HIGH); 
    digitalWrite(11,HIGH);  
      break; 
    case 5: 
      reset();  
    digitalWrite(9,HIGH); 
    digitalWrite(10,HIGH); 
    digitalWrite(11,HIGH); 
    digitalWrite(5,HIGH); 
    digitalWrite(7,HIGH);  
      break; 
    case 6: 
      reset();  
    digitalWrite(9,HIGH); 
    digitalWrite(10,HIGH); 
    digitalWrite(11,HIGH); 
    digitalWrite(5,HIGH); 
    digitalWrite(6,HIGH); 
    digitalWrite(7,HIGH);  
      break; 
    case 7: 
      reset();  
    digitalWrite(8,HIGH); 
    digitalWrite(5,HIGH); 
    digitalWrite(9,HIGH);  
      break; 
    case 8: 
      reset(); 
    digitalWrite(5,HIGH); 
    digitalWrite(6,HIGH); 
    digitalWrite(7,HIGH); 
    digitalWrite(8,HIGH); 
    digitalWrite(9,HIGH); 
    digitalWrite(10,HIGH); 
    digitalWrite(11,HIGH);  
      break; 
    case 9: 
      reset();  
    digitalWrite(5,HIGH); 
    digitalWrite(8,HIGH); 
    digitalWrite(9,HIGH); 
    digitalWrite(10,HIGH); 
    digitalWrite(11,HIGH);  
      break; 
     
  } 
 delay(125);
} 
void reset(){ 
digitalWrite(4,LOW); 
digitalWrite(5,LOW); 
digitalWrite(6,LOW); 
digitalWrite(7,LOW); 
digitalWrite(8,LOW); 
digitalWrite(9,LOW); 
digitalWrite(10,LOW); 
digitalWrite(11,LOW); 
}



