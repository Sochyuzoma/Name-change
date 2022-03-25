# Name-change
To change names on csv file

import pandas as pd
import csv
df = pd.read_csv(r'C:\Users\Sochi\Downloads\ALL.csv')
dg = df.replace({'NG-141510':'NG-306425','Lumartem 20/120mg x12':'Arenax Plus 20/120mg x12','NG-141511':'NG-306426','Lumartem 20/120mg x18':'Arenax Plus 20/120mg x18','NG-141512':'NG-306427','Lumartem 20/120mg x24':'Arenax Plus 20/120mg x24','NG-141509':'NG-306424','Lumartem 20/120mg x6':'Arenax Plus 20/120mg x6','NG-267378':'NG-306426','Macalum 20/120mg x18':'Arenax Plus 20/120mg x18','NG-267379':'NG-306427','Macalum 20/120mg x24':'Arenax Plus 20/120mg x24',
                 'NG-267380':'NG-306424','Macalum 20/120mg x6':'Arenax Plus 20/120mg x6',
                 'NG-126731':'NG-215424','Benylin (NGC) Expectorant 140mg/5ml x1':'Cough Expectorant (NGC) 100ml x1',
                 'NG-228079':'NG-284712','Pectol Eucalipto x 1':'Pectol Eucalipto x228',
                 'NG-167667':'NG-272820','Procold x4':'Procold x200','NG-160781':'NG-230086','Pregnancy test strip x50':'Pregnancy Test Strip (Assurance) x50',
                 'NG-190053':'NG-215892','Nerve and Bone 150ml x1':'Nerve Liniment (Moko) 200ml x1','NG-234966':'NG-302559'	,'Vitamin C and Glucose (Mekophar) x24':'Vitamin C/Glucose (Neros) 50mg/150mg x24',
                 'NG-215844':'NG-215433','Flu-J Syrup 100ml x1':'Flu J 100ml x1','NG-215196':'NG-272822','Mixadin x4':'Mixadin x100',
                 'NG-114690':'NG-266957','Albendazole (Zolat) 200mg/5ml x1':'Albendazole (Zolat) 100mg/5ml x1','NG-110448':'NG-224239','Calamine lotion 100ml x1':
'Calamine Lotion (Moko) x1', 'NG-269740':'NG-215330','Peak Milk Satchet':'Peak Milk Satchet x1','NG-215331':'NG-269676','Milo 20g x1':'Milo Satchet',
'NG-225201':'NG-110520','Folic acid + B12 (Dr. meyers) ×100':'Folic acid (Dr Meyer s) 5mg x100', 'NG-216175':'NG-270222','New Divine Tabs x 20':'Chest and Lungs Tablets (Divine) x20',
'NG-151223':'NG-215209'	,'Shal artem 140mg/5ml x1':'Shal artem Susp 180/1080mg x 1','NG-202514':'NG-301550','Levofem 0.15mg/0.03mg x28':'Levofem 0.15mg/0.03mg x84','NG-215348':'NG-269748','Raid 300 ml Insecticide Spray':'Raid 300 ml Insecticide Spray x1',
'NG-151270':'NG-297559','P-Alaxin 80/640 100ml x1':'P-Alaxin 80/640 80ml x1', 'NG-110508':'NG-269720','EMZOLYN (Emzolyn child) 7.55mg/5 ml x1':'Cough Syrup (Emzolyn Child) 7.55mg/5mlx1',
'NG-110441':'NG-132169','Benzyl Benzoate 100ml x1':'Benzyl Benzoate (Moko) 25%w/v 100ml x1'


})
# dg = df.replace({'NG-141510':'NG-271452','Lumartem 20/120mg x12':'Shalartem 20mg/120mg x12','NG-141511':'NG-269006','Lumartem 20/120mg x18':'Shalartem 20mg/120mg x18','NG-141512':'NG-306427','Lumartem 20/120mg x24':'Shalartem 20/120mg x24'})
dg.to_csv(r'C:\Users\Sochi\Documents\abuja_B\ALL.csv',index = False)
