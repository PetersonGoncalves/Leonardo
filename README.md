Leonardo
========

the leonardo controls your computers mouse and keyboard.

## mouse and click.ino

void setup()
{
  Mouse.begin();
  delay(1000);
  Mouse.move(200,100,0);
  Mouse.move(500,500,0);
  
}

void loop()
{
  delay(10);
}

