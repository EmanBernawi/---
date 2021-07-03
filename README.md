# ---
برمجة محركين DC 
الكود : 
int intp1 = 6; 
int intp2 = 5; 
int intp3 = 10;
int intp4 = 11; 
void setup(){
 pinMode (intp1, OUTPUT);
 pinMode (intp2, OUTPUT);
 pinMode (intp3, OUTPUT);
 pinMode (intp4, OUTPUT);
}
void loop(){
 digitalWrite (intp1 , HIGH);
 digitalWrite (intp2 , LOW);
 digitalWrite (intp3 , HIGH);
 digitalWrite (intp4 , LOW);
 delay (1000); 
 digitalWrite (intp1 , LOW);
 digitalWrite (intp2 , LOW);
 digitalWrite (intp3 , LOW);
 digitalWrite (intp4 , LOW);
 delay (1000);
}
