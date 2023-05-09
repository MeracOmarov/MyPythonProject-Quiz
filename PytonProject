q1=['Elektrik sahesinin dasiyicisi nedir?','elektrik yuku',100]
q2=['Maqnit sahesinin yuk dasiyicisi nedir?','maqnitler',200]
q3=['Elektromaqnit sahesinin yuk dasiyicisi nedir?','elektomaqnit dalgasi',300]
q4=['determinnant sifirdan boyukdurse onun nece koku var?','iki',500]
q5=['kadrat tenliyin kokleri ne zaman beraber olur?','diskriminant sifirdirsa',1000]
q6=['kadvat tenliyin ne zaman koku olmur?','diskriminant sifirdan kicikdirse',2000]
q7=['ingilise getmek nedir?','go',4000]
q8=['ingilis dilinde gelmek nedir?','come',8000]
q9=['how can I say in english --dunen--?','yesterday',16000]
q10=['ingilisce sabah nedir?','tomorrow',32000]
q11=['ingilisce sari reng nedir?  ','yellow',64000]
q12=['ingilisce mavi reng nedir?','blue',125000]
q13=['ingilisce menzil nedir? ','apartment',250000]
q14=['ingilisce deniz nedir ?','sea',500000]
q15=['ingilisce assembly nedir?','yigincaq',1000000]
common_score=0
print("""
SECIM:
1-imtina
2-dosta zeng
3-50/50
4-tamasacilar
5-musteqil
her secimden bir defe istifade etmek olar
""")
print('')
print('')
randomqs=[q1,q2,q3,q4,q5,q6,q7,q8,q9,q10,q11,q12,q13,q14,q15]
import random
for x in randomqs:
      
   if x==q1:    #####   QUESTION BIR  ############
      print('SUAL 1')
      print(x[0])
      print('')
      print('----cavablar----')
      print('')
      def fun0(sual_sual):
         global X2
         question_bank=[q1[1],q2[1],q3[1],q4[1],q5[1],q6[1],q7[1],q8[1],q9[1],q10[1],q11[1],q12[1],q13[1],q14[1],q15[1],"radiaoaktivlik"]
         question_bank.remove(sual_sual)
         random.shuffle(question_bank)
         X2=random.sample(question_bank,3)
         X2.insert(random.randint(1,4),sual_sual)
      fun0(q1[1])
      def fun1():
         global X2,ccc
         ccc=["A","B","C","D"]
         count=0
         for ff in X2:
            if count==0:
               print(f"A){ff}")
               count+=1
            elif count==1:
               print(f"B){ff}")
               count+=1
            elif count==2:
               print(f"C){ff}")
               count+=1
            elif count==3:
               print(f"D){ff}")
      fun1()
      while True:
           try:
            secim=int(input('secim edin'))
            break
           except:
            print('duzgun secim edin')
            continue
      if secim==1:# imtina etmek
         break
      elif secim==2:# dosta zeng
         x=random.choice(X2)
         print(f'--Dostun cavabi  ### {x} ### ')
         print('')
         while True:
            try:
             cavab=input('Cavabi daxil edin ').upper()
             break
            except:
             print('Cavabi duzgun daxil edin')
             continue
         ffff=ccc.index(cavab)
         if ffff==X2.index(q1[1]):
            print('---- siz 100 xal qazandiz -----')
            common_score+=100
            print(f'----- sizin scoreniz  {common_score}-----')
         else:
            print('cavab yalnisdir!!!!!!!')
            print('Oyun sona catdii')
            print(f'----- sizin scoreniz  {common_score}-----')
            break
            
            
      elif secim==3:# 50 50
         X2.remove(q1[1])
         X2.pop()
         X2.pop()
         X2.append(q1[1])
         count=0
         for hhh in X2:
            if count==0:
               print(f"A){hhh}")
               count+=1
            elif count==1:
               print(f"B){hhh}")

         while True:
            try:
             cavab=input('Cavabi daxil edin').upper()
             break
            except:
             print('cavabi duzgun daxil edin')
             continue
         ffff=ccc.index(cavab)
         if ffff==X2.index(q1[1]):
            print('---- siz 100 xal qazandiz ----')
            common_score+=100
            print(f'----- sizin scoreniz  {common_score}-----')
         else:
            print('cavab yalnisdir!!!!!!')
            print('Oyun sona catdii')
            print(f'----- sizin scoreniz  {common_score}-----')
            break   
      elif secim==4:# tamasacilar
         v=random.randint(10,100)
         x=random.choice(X2)
         print(f"Tamasacilar cavabin {v} faiz {x} oldugunu dusunur")
         while True:
            try:
             cavab=input('Cavabi daxil edin').upper()
             break
            except:
             print('Cavabi duzgun daxil edin')
             continue
         ffff=ccc.index(cavab)
         if ffff==X2.index(q1[1]):
            print('---- siz 100 xal qazandiz ---- ')
            common_score+=100
            print(f'----- sizin scoreniz  {common_score} -----')
         else:
            print('cavab yalnisdir!!!!!')
            print('Oyun sona catdii')
            print(f'----- sizin scoreniz  {common_score}-----')
            break   
      elif secim==5:# yourself
      
         while True:
            try:
             cavab=input('Cavabi daxil edin ').upper()
             break
            except:
             print('Cavabi duzgun daxil edin')
             continue
         ffff=ccc.index(cavab)
         if ffff==X2.index(q1[1]):
            print('---- siz 100 xal qazandiz ---- ')
            common_score+=100
            print(f'----- sizin scoreniz  {common_score} -----')
         else:
            print('cavab yalnisdir!!!!!!!')
            print('Oyun sona catdii')
            print(f'----- sizin scoreniz  {common_score}-----')
            break   


   elif x==q2: #######  QUESTION TWO #########
      print('SUAL 2')
      print(x[0])
      print('')
      print('---cavablar---')
      print('')
      fun0(q2[1])
      fun1()
      while True:
           try:
            secim=int(input('secim edin'))
            break
           except:
            print('duzgun secim edin')
            continue
      if secim==1:# imtina etmek
         break
      elif secim==2:# dosta zeng
         x=random.choice(X2)
         print(f'--Dostun cavabi  ### {x} ### ')
         print('')
         while True:
               try:
                  cavab=input('Cavabi daxil edin ').upper()
                  break
               except:
                  print('Cavabi duzgun daxil edin')
                  continue
         ffff=ccc.index(cavab)
         if ffff==X2.index(q2[1]):
            print('----siz 200 xal qazandiz----')
            common_score+=200
            print(f'sizin scoreniz  {common_score}')
         else:
            print('cavab yalnisdir!!!!!')
            print('Oyun sona catdii')
            print(f'----- sizin scoreniz  {common_score}-----')
            break   
      elif secim==3:# 50 50
         X2.remove(q2[1])
         X2.pop()
         X2.pop()
         X2.append(q2[1])
         count=0
         for hhh in X2:
            if count==0:
               print(f"A){hhh}")
               count+=1
            elif count==1:
               print(f"B){hhh}")

         while True:
               try:
                  cavab=input('Cavabi daxil edin ').upper()
                  break
               except:
                  print('Cavabi duzgun daxil edin')
                  continue
         ffff=ccc.index(cavab)
         if ffff==X2.index(q2[1]):
            print('---siz 200 xal qazandiz---')
            common_score+=200
            print(f'sizin scoreniz----{common_score}----')
         else:
            print('cavab yalnisdir!!!!')
            print('Oyun sona catdii')
            print(f'----- sizin scoreniz  {common_score}-----')
            break       
      elif secim==4:# tamasacilar
         v=random.randint(10,100)
         x=random.choice(X2)
         print(f"Tamasacilar cavabin {v} faiz -- {x} -- oldugunu dusunur")
         while True:
               try:
                  cavab=input('Cavabi daxil edin ').upper()
                  break
               except:
                  print('Cavabi duzgun daxil edin')
                  continue
         ffff=ccc.index(cavab)
         if ffff==X2.index(q2[1]):
            print('---siz 200 xal qazandiz---')
            common_score+=200
            print(f'sizin scoreniz  {common_score}')
         else:
            print('cavab yalnisdir!!!!!')
            print('Oyun sona catdii')
            print(f'----- sizin scoreniz  {common_score}-----')
            break   
      elif secim==5:# yourself
      
         while True:
               try:
                  cavab=input('Cavabi daxil edin ').upper()
                  break
               except:
                  print('Cavabi duzgun daxil edin')
                  continue
         ffff=ccc.index(cavab)
         if ffff==X2.index(q2[1]):
            print('---- siz 200 xal qazandiz ----')
            common_score+=200
            print(f'---- sizin scoreniz  {common_score} ----')
         else:
            print('cavab yalnisdir!!!!')
            print('Oyun sona catdii')
            print(f'----- sizin scoreniz  {common_score}-----')
            break   

   elif x==q3:##### QUESTION THREE #####
      print('SUAL 3')
      print(x[0])
      print('')
      print('cavablar')
      print('')
      fun0(q3[1])
      fun1()
      while True:
           try:
            secim=int(input('secim edin'))
            break
           except:
            print('duzgun secim edin')
            continue
      if secim==1:# imtina etmek
         break
      elif secim==2:# dosta zeng
         x=random.choice(X2)
         print(f'--Dostun cavabi  ### {x} ### ')
         print('')
         while True:
               try:
                  cavab=input('Cavabi daxil edin ').upper()
                  break
               except:
                  print('Cavabi duzgun daxil edin')
                  continue
         ffff=ccc.index(cavab)
         if ffff==X2.index(q3[1]):
            print('---siz 300 xal qazandiz---')
            common_score+=300
            print(f'----sizin scoreniz  {common_score}----')
         else:
            print('cavab yalnisdir!!!!')
            print('Oyun sona catdii')
            print(f'----- sizin scoreniz  {common_score}-----')
            break
      elif secim==3:# 50 50
         X2.remove(q3[1])
         X2.pop()
         X2.pop()
         X2.append(q3[1])
         count=0
         for hhh in X2:
            if count==0:
               print(f"A){hhh}")
               count+=1
            elif count==1:
               print(f"B){hhh}")

         while True:
               try:
                  cavab=input('Cavabi daxil edin ').upper()
                  break
               except:
                  print('Cavabi duzgun daxil edin')
                  continue
         ffff=ccc.index(cavab)
         if ffff==X2.index(q3[1]):
            print('---siz 300 xal qazandiz---')
            common_score+=300
            print(f'----sizin scoreniz  {common_score}----')
         else:
            print('cavab yalnisdir!!!!!')
            print('Oyun sona catdii')
            print(f'----- sizin scoreniz  {common_score}-----')
            break       
      elif secim==4:# tamasacilar
         v=random.randint(10,100)
         x=random.choice(X2)
         print(f"Tamasacilar cavabin {v} faiz -- {x} -- oldugunu dusunur")
         while True:
               try:
                  cavab=input('Cavabi daxil edin ').upper()
                  break
               except:
                  print('Cavabi duzgun daxil edin')
                  continue
         ffff=ccc.index(cavab)
         if ffff==X2.index(q3[1]):
            print('---siz 300 xal qazandiz---')
            common_score+=300
            print(f'-----sizin scoreniz  {common_score}----')
         else:
            print('cavab yalnisdir!!!!')
            print('Oyun sona catdii')
            print(f'----- sizin scoreniz  {common_score}-----')
            break   
      elif secim==5:# yourself
      
         while True:
               try:
                  cavab=input('Cavabi daxil edin ').upper()
                  break
               except:
                  print('Cavabi duzgun daxil edin')
                  continue
         ffff=ccc.index(cavab)
         if ffff==X2.index(q3[1]):
            print('----siz 300 xal qazandiz---')
            common_score+=300
            print(f'----sizin scoreniz  {common_score}-----')
         else:
            print('cavab yalnisdir!!!!!')
            print('Oyun sona catdii')
            print(f'----- sizin scoreniz  {common_score}-----')
            break   
   elif x==q4:######## QUESTION FOUR #########
      print('SUAL 4')
      print(x[0])
      print('')
      print('cavablar')
      print('')
      fun0(q4[1])
      fun1()
      while True:
            try:
               secim=int(input('secim edin'))
               break
            except:
               print('duzgun secim edin')
               continue
      if secim==1:# imtina etmek
         break
      elif secim==2:# dosta zeng
         x=random.choice(X2)
         print(f'--Dostun cavabi  ### {x} ### ')
         print('')
         while True:
               try:
                  cavab=input('Cavabi daxil edin ').upper()
                  break
               except:
                  print('Cavabi duzgun daxil edin')
                  continue
         ffff=ccc.index(cavab)
         if ffff==X2.index(q4[1]):
            print('---siz 300 xal qazandiz---')
            common_score+=500
            print(f'----sizin scoreniz  {common_score}----')
         else:
            print('cavab yalnisdir!!!!')
            print('Oyun sona catdii')
            print(f'----- sizin scoreniz  {common_score}-----')
            break   
      elif secim==3:# 50 50
         X2.remove(q4[1])
         X2.pop()
         X2.pop()
         X2.append(q4[1])
         count=0
         for hhh in X2:
            if count==0:
               print(f"A){hhh}")
               count+=1
            elif count==1:
               print(f"B){hhh}")

         while True:
               try:
                  cavab=input('Cavabi daxil edin ').upper()
                  break
               except:
                  print('Cavabi duzgun daxil edin')
                  continue
         ffff=ccc.index(cavab)
         if ffff==X2.index(q4[1]):
            print('---siz 500 xal qazandiz---')
            common_score+=500
            print(f'----sizin scoreniz  {common_score}----')
         else:
            print('cavab yalnisdir!!!!!')
            print('Oyun sona catdii')
            print(f'----- sizin scoreniz  {common_score}-----')
            break        
      elif secim==4:# tamasacilar
         v=random.randint(10,100)
         x=random.choice(X2)
         print(f"Tamasacilar cavabin {v} faiz -- {x} -- oldugunu dusunur")
         while True:
               try:
                  cavab=input('Cavabi daxil edin ').upper()
                  break
               except:
                  print('Cavabi duzgun daxil edin')
                  continue
         ffff=ccc.index(cavab)
         if ffff==X2.index(q4[1]):
            print('---siz 500 xal qazandiz---')
            common_score+=500
            print(f'-----sizin scoreniz  {common_score}----')
         else:
            print('cavab yalnisdir!!!!')
            print('Oyun sona catdii')
            print(f'----- sizin scoreniz  {common_score}-----')
            break   
      elif secim==5:# yourself
      
         while True:
               try:
                  cavab=input('Cavabi daxil edin ').upper()
                  break
               except:
                  print('Cavabi duzgun daxil edin')
                  continue
         ffff=ccc.index(cavab)
         if ffff==X2.index(q4[1]):
            print('----siz 500 xal qazandiz---')
            common_score+=500
            print(f'----sizin scoreniz  {common_score}-----')
         else:
            print('cavab yalnisdir!!!!!')
            print('Oyun sona catdii')
            print(f'----- sizin scoreniz  {common_score}-----')
            break   
   elif x==q5:########## QUESTION FIVE #########
      print('SUAL 5')
      print(x[0])
      print('')
      print('cavablar')
      print('')
      fun0(q5[1])
      fun1()
      while True:
            try:
               secim=int(input('secim edin'))
               break
            except:
               print('duzgun secim edin')
               continue
      if secim==1:# imtina etmek
         break
      elif secim==2:# dosta zeng
         x=random.choice(X2)
         print(f'--Dostun cavabi  ### {x} ### ')
         print('')
         while True:
               try:
                  cavab=input('Cavabi daxil edin ').upper()
                  break
               except:
                  print('Cavabi duzgun daxil edin')
                  continue
         ffff=ccc.index(cavab)
         if ffff==X2.index(q5[1]):
            print('---siz 1000 xal qazandiz---')
            common_score+=1000
            print(f'----sizin scoreniz  {common_score}----')
         else:
            print('cavab yalnisdir!!!!')
            print('Oyun sona catdii')
            print(f'----- sizin scoreniz  {common_score}-----')
            break   
      elif secim==3:# 50 50
         X2.remove(q5[1])
         X2.pop()
         X2.pop()
         X2.append(q5[1])
         count=0
         for hhh in X2:
            if count==0:
               print(f"A){hhh}")
               count+=1
            elif count==1:
               print(f"B){hhh}")

         while True:
               try:
                  cavab=input('Cavabi daxil edin ').upper()
                  break
               except:
                  print('Cavabi duzgun daxil edin')
                  continue
         ffff=ccc.index(cavab)
         if ffff==X2.index(q5[1]):
            print('---siz 1000 xal qazandiz---')
            common_score+=1000
            print(f'----sizin scoreniz  {common_score}----')
         else:
            print('cavab yalnisdir!!!!!')
            print('Oyun sona catdii')
            print(f'----- sizin scoreniz  {common_score}-----')
            break        
      elif secim==4:# tamasacilar
         v=random.randint(10,100)
         x=random.choice(X2)
         print(f"Tamasacilar cavabin {v} faiz -- {x} -- oldugunu dusunur")
         while True:
               try:
                  cavab=input('Cavabi daxil edin ').upper()
                  break
               except:
                  print('Cavabi duzgun daxil edin')
                  continue
         ffff=ccc.index(cavab)
         if ffff==X2.index(q5[1]):
            print('---siz 1000 xal qazandiz---')
            common_score+=1000
            print(f'-----sizin scoreniz  {common_score}----')
         else:
            print('cavab yalnisdir!!!!')
            print('Oyun sona catdii')
            print(f'----- sizin scoreniz  {common_score}-----')
            break   
      elif secim==5:# yourself
      
         while True:
               try:
                  cavab=input('Cavabi daxil edin ').upper()
                  break
               except:
                  print('Cavabi duzgun daxil edin')
                  continue
         ffff=ccc.index(cavab)
         if ffff==X2.index(q5[1]):
            print('----siz 1000 xal qazandiz---')
            common_score+=1000
            print(f'----sizin scoreniz  {common_score}-----')
         else:
            print('cavab yalnisdir!!!!!')
            print('Oyun sona catdii')
            print(f'----- sizin scoreniz  {common_score}-----')
            break         
   elif x==q6:####### QUESTION SIX ########
      print('SUAL 6')
      print(x[0])
      print('')
      print('cavablar')
      print('')
      fun0(q6[1])
      fun1()
      while True:
            try:
               secim=int(input('secim edin'))
               break
            except:
               print('duzgun secim edin')
               continue
      if secim==1:# imtina etmek
         break
      elif secim==2:# dosta zeng
         x=random.choice(X2)
         print(f'--Dostun cavabi  ### {x} ### ')
         print('')
         while True:
               try:
                  cavab=input('Cavabi daxil edin ').upper()
                  break
               except:
                  print('Cavabi duzgun daxil edin')
                  continue
         ffff=ccc.index(cavab)
         if ffff==X2.index(q6[1]):
            print('---siz 2000 xal qazandiz---')
            common_score+=2000
            print(f'----sizin scoreniz  {common_score}----')
         else:
            print('cavab yalnisdir!!!!')
            print('Oyun sona catdii')
            print(f'----- sizin scoreniz  {common_score}-----')
            break   
      elif secim==3:# 50 50
         X2.remove(q6[1])
         X2.pop()
         X2.pop()
         X2.append(q6[1])
         count=0
         for hhh in X2:
            if count==0:
               print(f"A){hhh}")
               count+=1
            elif count==1:
               print(f"B){hhh}")

         while True:
               try:
                  cavab=input('Cavabi daxil edin ').upper()
                  break
               except:
                  print('Cavabi duzgun daxil edin')
                  continue
         ffff=ccc.index(cavab)
         if ffff==X2.index(q6[1]):
            print('---siz 2000 xal qazandiz---')
            common_score+=2000
            print(f'----sizin scoreniz  {common_score}----')
         else:
            print('cavab yalnisdir!!!!!')
            print('Oyun sona catdii')
            print(f'----- sizin scoreniz  {common_score}-----')
            break        
      elif secim==4:# tamasacilar
         v=random.randint(10,100)
         x=random.choice(X2)
         print(f"Tamasacilar cavabin {v} faiz -- {x} -- oldugunu dusunur")
         while True:
               try:
                  cavab=input('Cavabi daxil edin ').upper()
                  break
               except:
                  print('Cavabi duzgun daxil edin')
                  continue
         ffff=ccc.index(cavab)
         if ffff==X2.index(q6[1]):
            print('---siz 2000 xal qazandiz---')
            common_score+=2000
            print(f'-----sizin scoreniz  {common_score}----')
         else:
            print('cavab yalnisdir!!!!')
            print('Oyun sona catdii')
            print(f'----- sizin scoreniz  {common_score}-----')
            break   
      elif secim==5:# yourself
      
         while True:
               try:
                  cavab=input('Cavabi daxil edin ').upper()
                  break
               except:
                  print('Cavabi duzgun daxil edin')
                  continue
         ffff=ccc.index(cavab)
         if ffff==X2.index(q6[1]):
            print('----siz 2000 xal qazandiz---')
            common_score+=2000
            print(f'----sizin scoreniz  {common_score}-----')
         else:
            print('cavab yalnisdir!!!!!')
            print('Oyun sona catdii')
            print(f'----- sizin scoreniz  {common_score}-----')
            break     
   elif x==q7:####### QUESTION SEVEN #######
      print('SUAL 7')
      print(x[0])
      print('')
      print('cavablar')
      print('')
      fun0(q7[1])
      fun1()
      while True:
            try:
               secim=int(input('secim edin'))
               break
            except:
               print('duzgun secim edin')
               continue
      if secim==1:# imtina etmek
         break
      elif secim==2:# dosta zeng
         x=random.choice(X2)
         print(f'--Dostun cavabi  ### {x} ### ')
         print('')
         while True:
               try:
                  cavab=input('Cavabi daxil edin ').upper()
                  break
               except:
                  print('Cavabi duzgun daxil edin')
                  continue
         ffff=ccc.index(cavab)
         if ffff==X2.index(q7[1]):
            print('---siz 2000 xal qazandiz---')
            common_score+=2000
            print(f'----sizin scoreniz  {common_score}----')
         else:
            print('cavab yalnisdir!!!!')
            print('Oyun sona catdii')
            print(f'----- sizin scoreniz  {common_score}-----')
            break   
      elif secim==3:# 50 50
         X2.remove(q7[1])
         X2.pop()
         X2.pop()
         X2.append(q7[1])
         count=0
         for hhh in X2:
            if count==0:
               print(f"A){hhh}")
               count+=1
            elif count==1:
               print(f"B){hhh}")

         while True:
               try:
                  cavab=input('Cavabi daxil edin ').upper()
                  break
               except:
                  print('Cavabi duzgun daxil edin')
                  continue
         ffff=ccc.index(cavab)
         if ffff==X2.index(q7[1]):
            print('---siz 4000 xal qazandiz---')
            common_score+=4000
            print(f'----sizin scoreniz  {common_score}----')
         else:
            print('cavab yalnisdir!!!!!')
            print('Oyun sona catdii')
            print(f'----- sizin scoreniz  {common_score}-----')
            break       
      elif secim==4:# tamasacilar
         v=random.randint(10,100)
         x=random.choice(X2)
         print(f"Tamasacilar cavabin {v} faiz -- {x} -- oldugunu dusunur")
         cavab=input('cvabi daxil edin')
         ffff=ccc.index(cavab)
         if ffff==X2.index(q7[1]):
            print('---siz 4000 xal qazandiz---')
            common_score+=4000
            print(f'-----sizin scoreniz  {common_score}----')
         else:
            print('cavab yalnisdir!!!!')
            print('Oyun sona catdii')
            print(f'----- sizin scoreniz  {common_score}-----')
            break   
      elif secim==5:# yourself
      
         while True:
               try:
                  cavab=input('Cavabi daxil edin ').upper()
                  break
               except:
                  print('Cavabi duzgun daxil edin')
                  continue
         ffff=ccc.index(cavab)
         if ffff==X2.index(q7[1]):
            print('----siz 4000 xal qazandiz---')
            common_score+=4000
            print(f'----sizin scoreniz  {common_score}-----')
         else:
            print('cavab yalnisdir!!!!!')
            print('Oyun sona catdii')
            print(f'----- sizin scoreniz  {common_score}-----')
            break    
   elif x==q8:######## QUESTION EIGHT #########
      print('SUAL 8')
      print(x[0])
      print('')
      print('cavablar')
      print('')
      fun0(q8[1])
      fun1()
      while True:
            try:
               secim=int(input('secim edin'))
               break
            except:
               print('duzgun secim edin')
               continue
      if secim==1:# imtina etmek
         break
      elif secim==2:# dosta zeng
         x=random.choice(X2)
         print(f'--Dostun cavabi  ### {x} ### ')
         print('')
         cavab=input('cvabi daxil edin').upper()
         ffff=ccc.index(cavab)
         if ffff==X2.index(q8[1]):
            print('---siz 1000 xal qazandiz---')
            common_score+=8000
            print(f'----sizin scoreniz  {common_score}----')
         else:
            print('cavab yalnisdir!!!!')
            print('Oyun sona catdii')
            print(f'----- sizin scoreniz  {common_score}-----')
            break   
      elif secim==3:# 50 50
         X2.remove(q8[1])
         X2.pop()
         X2.pop()
         X2.append(q8[1])
         count=0
         for hhh in X2:
            if count==0:
               print(f"A){hhh}")
               count+=1
            elif count==1:
               print(f"B){hhh}")

         while True:
               try:
                  cavab=input('Cavabi daxil edin ').upper()
                  break
               except:
                  print('Cavabi duzgun daxil edin')
                  continue
         ffff=ccc.index(cavab)
         if ffff==X2.index(q8[1]):
            print('---siz 8000 xal qazandiz---')
            common_score+=8000
            print(f'----sizin scoreniz  {common_score}----')
         else:
            print('cavab yalnisdir!!!!!')
            print('Oyun sona catdii')
            print(f'----- sizin scoreniz  {common_score}-----')
            break        
      elif secim==4:# tamasacilar
         v=random.randint(10,100)
         x=random.choice(X2)
         print(f"Tamasacilar cavabin {v} faiz -- {x} -- oldugunu dusunur")
         cavab=input('cvabi daxil edin')
         ffff=ccc.index(cavab)
         if ffff==X2.index(q8[1]):
            print('---siz 8000 xal qazandiz---')
            common_score+=8000
            print(f'-----sizin scoreniz  {common_score}----')
         else:
            print('cavab yalnisdir!!!!')
            print('Oyun sona catdii')
            print(f'----- sizin scoreniz  {common_score}-----')
            break   
      elif secim==5:# yourself
      
         while True:
               try:
                  cavab=input('Cavabi daxil edin ').upper()
                  break
               except:
                  print('Cavabi duzgun daxil edin')
                  continue
         ffff=ccc.index(cavab)
         if ffff==X2.index(q8[1]):
            print('----siz 8000 xal qazandiz---')
            common_score+=8000
            print(f'----sizin scoreniz  {common_score}-----')
         else:
            print('cavab yalnisdir!!!!!')
            print('Oyun sona catdii')
            print(f'----- sizin scoreniz  {common_score}-----')
            break     
   elif x==q9:###### QUESTION NINE #########
      print('SUAL 9')
      print(x[0])
      print('')
      print('cavablar')
      print('')
      fun0(q9[1])
      fun1()
      while True:
            try:
               secim=int(input('secim edin'))
               break
            except:
               print('duzgun secim edin')
               continue
      if secim==1:# imtina etmek
         break
      elif secim==2:# dosta zeng
         x=random.choice(X2)
         print(f'--Dostun cavabi  ### {x} ### ')
         print('')
         while True:
               try:
                  cavab=input('Cavabi daxil edin ').upper()
                  break
               except:
                  print('Cavabi duzgun daxil edin')
                  continue
         ffff=ccc.index(cavab)
         if ffff==X2.index(q9[1]):
            print('---siz 16000 xal qazandiz---')
            common_score+=16000
            print(f'----sizin scoreniz  {common_score}----')
         else:
            print('cavab yalnisdir!!!!')
            print('Oyun sona catdii')
            print(f'----- sizin scoreniz  {common_score}-----')
            break   
      elif secim==3:# 50 50
         X2.remove(q9[1])
         X2.pop()
         X2.pop()
         X2.append(q9[1])
         count=0
         for hhh in X2:
            if count==0:
               print(f"A){hhh}")
               count+=1
            elif count==1:
               print(f"B){hhh}")

         while True:
               try:
                  cavab=input('Cavabi daxil edin ').upper()
                  break
               except:
                  print('Cavabi duzgun daxil edin')
                  continue
         ffff=ccc.index(cavab)
         if ffff==X2.index(q9[1]):
            print('---siz 16000 xal qazandiz---')
            common_score+=16000
            print(f'----sizin scoreniz  {common_score}----')
         else:
            print('cavab yalnisdir!!!!!')
            print('Oyun sona catdii')
            print(f'----- sizin scoreniz  {common_score}-----')
            break        
      elif secim==4:# tamasacilar
         v=random.randint(10,100)
         x=random.choice(X2)
         print(f"Tamasacilar cavabin {v} faiz -- {x} -- oldugunu dusunur")
         while True:
               try:
                  cavab=input('Cavabi daxil edin ').upper()
                  break
               except:
                  print('Cavabi duzgun daxil edin')
                  continue
         ffff=ccc.index(cavab)
         if ffff==X2.index(q9[1]):
            print('---siz 16000 xal qazandiz---')
            common_score+=16000
            print(f'-----sizin scoreniz  {common_score}----')
         else:
            print('cavab yalnisdir!!!!')
            print('Oyun sona catdii')
            print(f'----- sizin scoreniz  {common_score}-----')
            break   
      elif secim==5:# yourself
      
         while True:
               try:
                  cavab=input('Cavabi daxil edin ').upper()
                  break
               except:
                  print('Cavabi duzgun daxil edin')
                  continue
         ffff=ccc.index(cavab)
         if ffff==X2.index(q9[1]):
            print('----siz 16000 xal qazandiz---')
            common_score+=16000
            print(f'----sizin scoreniz  {common_score}-----')
         else:
            print('cavab yalnisdir!!!!!')
            print('Oyun sona catdii')
            print(f'----- sizin scoreniz  {common_score}-----')
            break              
   elif x==q10:####### QUESTION TEN #######
      print('SUAL 10')
      print(x[0])
      print('')
      print('cavablar')
      print('')
      fun0(q10[1])
      fun1()
      while True:
            try:
               secim=int(input('secim edin'))
               break
            except:
               print('duzgun secim edin')
               continue
      if secim==1:# imtina etmek
         break
      elif secim==2:# dosta zeng
         x=random.choice(X2)
         print(f'--Dostun cavabi  ### {x} ### ')
         print('')
         cavab=input('cvabi daxil edin').upper()
         ffff=ccc.index(cavab)
         if ffff==X2.index(q10[1]):
            print('---siz 32000 xal qazandiz---')
            common_score+=32000
            print(f'----sizin scoreniz  {common_score}----')
         else:
            print('cavab yalnisdir!!!!')
            print('Oyun sona catdii')
            print(f'----- sizin scoreniz  {common_score}-----')
            break   
      elif secim==3:# 50 50
         X2.remove(q10[1])
         X2.pop()
         X2.pop()
         X2.append(q10[1])
         count=0
         for hhh in X2:
            if count==0:
               print(f"A){hhh}")
               count+=1
            elif count==1:
               print(f"B){hhh}")

         while True:
               try:
                  cavab=input('Cavabi daxil edin ').upper()
                  break
               except:
                  print('Cavabi duzgun daxil edin')
                  continue
         ffff=ccc.index(cavab)
         if ffff==X2.index(q10[1]):
            print('---siz 32000 xal qazandiz---')
            common_score+=32000
            print(f'----sizin scoreniz  {common_score}----')
         else:
            print('cavab yalnisdir!!!!!')
            print('Oyun sona catdii')
            print(f'----- sizin scoreniz  {common_score}-----')
            break        
      elif secim==4:# tamasacilar
         v=random.randint(10,100)
         x=random.choice(X2)
         print(f"Tamasacilar cavabin {v} faiz -- {x} -- oldugunu dusunur")
         while True:
               try:
                  cavab=input('Cavabi daxil edin ').upper()
                  break
               except:
                  print('Cavabi duzgun daxil edin')
                  continue
         ffff=ccc.index(cavab)
         if ffff==X2.index(q10[1]):
            print('---siz 32000 xal qazandiz---')
            common_score+=32000
            print(f'-----sizin scoreniz  {common_score}----')
         else:
            print('cavab yalnisdir!!!!')
            print('Oyun sona catdii')
            print(f'----- sizin scoreniz  {common_score}-----')
            break   
      elif secim==5:# yourself
      
         while True:
               try:
                  cavab=input('Cavabi daxil edin ').upper()
                  break
               except:
                  print('Cavabi duzgun daxil edin')
                  continue
         ffff=ccc.index(cavab)
         if ffff==X2.index(q10[1]):
            print('----siz 32000 xal qazandiz---')
            common_score+=32000
            print(f'----sizin scoreniz  {common_score}-----')
         else:
            print('cavab yalnisdir!!!!!')
            print('Oyun sona catdii')
            print(f'----- sizin scoreniz  {common_score}-----')
            break      
            
   elif x==q11:######## QUESTION ELEVEN #######
      print('SUAL 11')
      print(x[0])
      print('')
      print('cavablar')
      print('')
      fun0(q11[1])
      fun1()
      while True:
            try:
               secim=int(input('secim edin'))
               break
            except:
               print('duzgun secim edin')
               continue
      if secim==1:# imtina etmek
         break
      elif secim==2:# dosta zeng
         x=random.choice(X2)
         print(f'--Dostun cavabi  ### {x} ### ')
         print('')
         cavab=input('cvabi daxil edin').upper()
         ffff=ccc.index(cavab)
         if ffff==X2.index(q11[1]):
            print('---siz 64000 xal qazandiz---')
            common_score+=64000
            print(f'----sizin scoreniz  {common_score}----')
         else:
            print('cavab yalnisdir!!!!')
            print('Oyun sona catdii')
            print(f'----- sizin scoreniz  {common_score}-----')
            break   
      elif secim==3:# 50 50
         X2.remove(q11[1])
         X2.pop()
         X2.pop()
         X2.append(q11[1])
         count=0
         for hhh in X2:
            if count==0:
               print(f"A){hhh}")
               count+=1
            elif count==1:
               print(f"B){hhh}")

         while True:
               try:
                  cavab=input('Cavabi daxil edin ').upper()
                  break
               except:
                  print('Cavabi duzgun daxil edin')
                  continue
         ffff=ccc.index(cavab)
         if ffff==X2.index(q11[1]):
            print('---siz 16000 xal qazandiz---')
            common_score+=64000
            print(f'----sizin scoreniz  {common_score}----')
         else:
            print('cavab yalnisdir!!!!!')
            print('Oyun sona catdii')
            print(f'----- sizin scoreniz  {common_score}-----')
            break        
      elif secim==4:# tamasacilar
         v=random.randint(10,100)
         x=random.choice(X2)
         print(f"Tamasacilar cavabin {v} faiz -- {x} -- oldugunu dusunur")
         cavab=input('cvabi daxil edin').upper()
         ffff=ccc.index(cavab)
         if ffff==X2.index(q11[1]):
            print('---siz 64000 xal qazandiz---')
            common_score+=64000
            print(f'-----sizin scoreniz  {common_score}----')
         else:
            print('cavab yalnisdir!!!!')
            print('Oyun sona catdii')
            print(f'----- sizin scoreniz  {common_score}-----')
            break   
      elif secim==5:# yourself
      
         while True:
               try:
                  cavab=input('Cavabi daxil edin ').upper()
                  break
               except:
                  print('Cavabi duzgun daxil edin')
                  continue
         ffff=ccc.index(cavab)
         if ffff==X2.index(q11[1]):
            print('----siz 64000 xal qazandiz---')
            common_score+=64000
            print(f'----sizin scoreniz  {common_score}-----')
         else:
            print('cavab yalnisdir!!!!!')
            print('Oyun sona catdii')
            print(f'----- sizin scoreniz  {common_score}-----')
            break      
   elif x==q12: ###### QUESTION TWELVE ######
      print('SUAL 12')
      print(x[0])
      print('')
      print('cavablar')
      print('')
      fun0(q12[1])
      fun1()
      while True:
            try:
               secim=int(input('secim edin'))
               break
            except:
               print('duzgun secim edin')
               continue
      if secim==1:# imtina etmek
         break
      elif secim==2:# dosta zeng
         x=random.choice(X2)
         print(f'--Dostun cavabi  ### {x} ### ')
         print('')
         cavab=input('cvabi daxil edin').upper()
         ffff=ccc.index(cavab)
         if ffff==X2.index(q12[1]):
            print('---siz 125000 xal qazandiz---')
            common_score+=125000
            print(f'----sizin scoreniz  {common_score}----')
         else:
            print('cavab yalnisdir!!!!')
            print('Oyun sona catdii')
            print(f'----- sizin scoreniz  {common_score}-----')
            break   
      elif secim==3:# 50 50
         X2.remove(q12[1])
         X2.pop()
         X2.pop()
         X2.append(q12[1])
         count=0
         for hhh in X2:
            if count==0:
               print(f"A){hhh}")
               count+=1
            elif count==1:
               print(f"B){hhh}")

         while True:
               try:
                  cavab=input('Cavabi daxil edin ').upper()
                  break
               except:
                  print('Cavabi duzgun daxil edin')
                  continue
         ffff=ccc.index(cavab)
         if ffff==X2.index(q12[1]):
            print('---siz 125000 xal qazandiz---')
            common_score+=125000
            print(f'----sizin scoreniz  {common_score}----')
         else:
            print('cavab yalnisdir!!!!!')
            print('Oyun sona catdii')
            print(f'----- sizin scoreniz  {common_score}-----')
            break        
      elif secim==4:# tamasacilar
         v=random.randint(10,100)
         x=random.choice(X2)
         print(f"Tamasacilar cavabin {v} faiz -- {x} -- oldugunu dusunur")
         while True:
               try:
                  cavab=input('Cavabi daxil edin ').upper()
                  break
               except:
                  print('Cavabi duzgun daxil edin')
                  continue
         ffff=ccc.index(cavab)
         if ffff==X2.index(q12[1]):
            print('---siz 125000 xal qazandiz---')
            common_score+=125000
            print(f'-----sizin scoreniz  {common_score}----')
         else:
            print('cavab yalnisdir!!!!')
            print('Oyun sona catdii')
            print(f'----- sizin scoreniz  {common_score}-----')
            break   
      elif secim==5:# yourself
      
         while True:
               try:
                  cavab=input('Cavabi daxil edin ').upper()
                  break
               except:
                  print('Cavabi duzgun daxil edin')
                  continue
         ffff=ccc.index(cavab)
         if ffff==X2.index(q12[1]):
            print('----siz 125000 xal qazandiz---')
            common_score+=125000
            print(f'----sizin scoreniz  {common_score}-----')
         else:
            print('cavab yalnisdir!!!!!')
            print('Oyun sona catdii')
            print(f'----- sizin scoreniz  {common_score}-----')
            break      
   elif x==q13:####### QUESTION THIRDTEEN ####
      print('SUAL 13')
      print(x[0])
      print('')
      print('cavablar')
      print('')
      fun0(q13[1])
      fun1()
      while True:
            try:
               secim=int(input('secim edin'))
               break
            except:
               print('duzgun secim edin')
               continue
      if secim==1:# imtina etmek
         break
      elif secim==2:# dosta zeng
         x=random.choice(X2)
         print(f'--Dostun cavabi  ### {x} ### ')
         print('')
         while True:
               try:
                  cavab=input('Cavabi daxil edin ').upper()
                  break
               except:
                  print('Cavabi duzgun daxil edin')
                  continue
         ffff=ccc.index(cavab)
         if ffff==X2.index(q13[1]):
            print('---siz 250000 xal qazandiz---')
            common_score+=250000
            print(f'----sizin scoreniz  {common_score}----')
         else:
            print('cavab yalnisdir!!!!')
            print('Oyun sona catdii')
            print(f'----- sizin scoreniz  {common_score}-----')
            break   
      elif secim==3:# 50 50
         X2.remove(q13[1])
         X2.pop()
         X2.pop()
         X2.append(q13[1])
         count=0
         for hhh in X2:
            if count==0:
               print(f"A){hhh}")
               count+=1
            elif count==1:
               print(f"B){hhh}")

         while True:
               try:
                  cavab=input('Cavabi daxil edin ').upper()
                  break
               except:
                  print('Cavabi duzgun daxil edin')
                  continue
         ffff=ccc.index(cavab)
         if ffff==X2.index(q13[1]):
            print('---siz 250000 xal qazandiz---')
            common_score+=250000
            print(f'----sizin scoreniz  {common_score}----')
         else:
            print('cavab yalnisdir!!!!!')
            print('Oyun sona catdii')
            print(f'----- sizin scoreniz  {common_score}-----')
            break        
      elif secim==4:# tamasacilar
         v=random.randint(10,100)
         x=random.choice(X2)
         print(f"Tamasacilar cavabin {v} faiz -- {x} -- oldugunu dusunur")
         cavab=input('cvabi daxil edin').upper()
         ffff=ccc.index(cavab)
         if ffff==X2.index(q13[1]):
            print('---siz 250000 xal qazandiz---')
            common_score+=16000
            print(f'-----sizin scoreniz  {common_score}----')
         else:
            print('cavab yalnisdir!!!!')
            print('Oyun sona catdii')
            print(f'----- sizin scoreniz  {common_score}-----')
            break   
      elif secim==5:# yourself
      
         while True:
               try:
                  cavab=input('Cavabi daxil edin ').upper()
                  break
               except:
                  print('Cavabi duzgun daxil edin')
                  continue
         ffff=ccc.index(cavab)
         if ffff==X2.index(q13[1]):
            print('----siz 250000 xal qazandiz---')
            common_score+=250000
            print(f'----sizin scoreniz  {common_score}-----')
         else:
            print('cavab yalnisdir!!!!!')
            print('Oyun sona catdii')
            print(f'----- sizin scoreniz  {common_score}-----')
            break      
   elif x==q14:###### QUESTION FOURTEEN ######
      print('SUAL 14')
      print(x[0])
      print('')
      print('cavablar')
      print('')
      fun0(q14[1])
      fun1()
      while True:
            try:
               secim=int(input('secim edin'))
               break
            except:
               print('duzgun secim edin')
               continue
      if secim==1:# imtina etmek
         break
      elif secim==2:# dosta zeng
         x=random.choice(X2)
         print(f'--Dostun cavabi  ### {x} ### ')
         print('')
         while True:
               try:
                  cavab=input('Cavabi daxil edin ').upper()
                  break
               except:
                  print('Cavabi duzgun daxil edin')
                  continue
         ffff=ccc.index(cavab)
         if ffff==X2.index(q14[1]):
            print('---siz 500000 xal qazandiz---')
            common_score+=500000
            print(f'----sizin scoreniz  {common_score}----')
         else:
            print('cavab yalnisdir!!!!')
            print('Oyun sona catdii')
            print(f'----- sizin scoreniz  {common_score}-----')
            break   
      elif secim==3:# 50 50
         X2.remove(q14[1])
         X2.pop()
         X2.pop()
         X2.append(q14[1])
         count=0
         for hhh in X2:
            if count==0:
               print(f"A){hhh}")
               count+=1
            elif count==1:
               print(f"B){hhh}")

         while True:
               try:
                  cavab=input('Cavabi daxil edin ').upper()
                  break
               except:
                  print('Cavabi duzgun daxil edin')
                  continue
         ffff=ccc.index(cavab)
         if ffff==X2.index(q14[1]):
            print('---siz 500000 xal qazandiz---')
            common_score+=500000
            print(f'----sizin scoreniz  {common_score}----')
         else:
            print('cavab yalnisdir!!!!!')
            print('Oyun sona catdii')
            print(f'----- sizin scoreniz  {common_score}-----')
            break        
      elif secim==4:# tamasacilar
         v=random.randint(10,100)
         x=random.choice(X2)
         print(f"Tamasacilar cavabin {v} faiz -- {x} -- oldugunu dusunur")
         while True:
               try:
                  cavab=input('Cavabi daxil edin ').upper()
                  break
               except:
                  print('Cavabi duzgun daxil edin')
                  continue
         ffff=ccc.index(cavab)
         if ffff==X2.index(q14[1]):
            print('---siz 500000 xal qazandiz---')
            common_score+=500000
            print(f'-----sizin scoreniz  {common_score}----')
         else:
            print('cavab yalnisdir!!!!')
            print('Oyun sona catdii')
            print(f'----- sizin scoreniz  {common_score}-----')
            break   
      elif secim==5:# yourself
      
         while True:
               try:
                  cavab=input('Cavabi daxil edin ').upper()
                  break
               except:
                  print('Cavabi duzgun daxil edin')
                  continue
         ffff=ccc.index(cavab)
         if ffff==X2.index(q14[1]):
            print('----siz 500000 xal qazandiz---')
            common_score+=500000
            print(f'----sizin scoreniz  {common_score}-----')
         else:
            print('cavab yalnisdir!!!!!')
            print('Oyun sona catdii')
            print(f'----- sizin scoreniz  {common_score}-----')
            break      
   elif x==q15:##### QUESTION FIFTEEN #####
      print('SUAL 15')
      print(x[0])
      print('')
      print('cavablar')
      print('')
      fun0(q15[1])
      fun1()
      while True:
            try:
               secim=int(input('secim edin'))
               break
            except:
               print('duzgun secim edin')
               continue
      if secim==1:# imtina etmek
         break
      elif secim==2:# dosta zeng
         x=random.choice(X2)
         print(f'--Dostun cavabi  ### {x} ### ')
         print('')
         while True:
               try:
                  cavab=input('Cavabi daxil edin ').upper()
                  break
               except:
                  print('Cavabi duzgun daxil edin')
                  continue
         ffff=ccc.index(cavab)
         if ffff==X2.index(q15[1]):
            print('---siz 1000000 xal qazandiz---')
            common_score+=1000000
            print(f'----sizin scoreniz  {common_score}----')
         else:
            print('cavab yalnisdir!!!!')
            print('Oyun sona catdii')
            print(f'----- sizin scoreniz  {common_score}-----')
            break   
      elif secim==3:# 50 50
         X2.remove(q15[1])
         X2.pop()
         X2.pop()
         X2.append(q15[1])
         count=0
         for hhh in X2:
            if count==0:
               print(f"A){hhh}")
               count+=1
            elif count==1:
               print(f"B){hhh}")

         while True:
               try:
                  cavab=input('Cavabi daxil edin ').upper()
                  break
               except:
                  print('Cavabi duzgun daxil edin')
                  continue
         ffff=ccc.index(cavab)
         if ffff==X2.index(q15[1]):
            print('---siz 1000000 xal qazandiz---')
            common_score+=1000000
            print(f'----sizin scoreniz  {common_score}----')
         else:
            print('cavab yalnisdir!!!!!') 
            print('Oyun sona catdii')
            print(f'----- sizin scoreniz  {common_score}-----')
            break       
      elif secim==4:# tamasacilar
         v=random.randint(10,100)
         x=random.choice(X2)
         print(f"Tamasacilar cavabin {v} faiz -- {x} -- oldugunu dusunur")
         while True:
               try:
                  cavab=input('Cavabi daxil edin ').upper()
                  break
               except:
                  print('Cavabi duzgun daxil edin')
                  continue
         ffff=ccc.index(cavab)
         if ffff==X2.index(q15[1]):
            print('---siz 1000000 xal qazandiz---')
            common_score+=1000000
            print(f'-----sizin scoreniz  {common_score}----')
         else:
            print('cavab yalnisdir!!!!')
            print('Oyun sona catdii')
            print(f'----- sizin scoreniz  {common_score}-----')
            break   
      elif secim==5:# yourself
         
         while True:
               try:
                  cavab=input('Cavabi daxil edin ').upper()
                  break
               except:
                  print('Cavabi duzgun daxil edin')
                  continue
         ffff=ccc.index(cavab)
         if ffff==X2.index(q15[1]):
            print('----siz 1000000 xal qazandiz---')
            common_score+=1000000
            print(f'----sizin scoreniz  {common_score}-----')
         else:
            print('cavab yalnisdir!!!!!')
            print('Oyun sona catdii')
            print(f'----- sizin scoreniz  {common_score}-----')
            break      
         
      
      
                           





