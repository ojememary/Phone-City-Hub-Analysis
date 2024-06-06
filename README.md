# Phone-City-Hub-Analysis
Sales Analysis about a phone company in Lagos, Nigeria.

 
## Dataset Overview:
The dataset I used covers sales data from January to October 2023, featuring five popular phone brands: iPhone, Samsung, Infinix, Tecno, and Itel. Here’s a breakdown:
Time Period: January 2023 to October 2023
Regions: North, South, East, West
Products: iPhone, Samsung, Infinix, Tecno, Itel
Metrics: Units Sold, Revenue

## Tools
- Microsoft Excel
- VBA
- MACROS
  ## VBA CODE

  Option Explicit
Sub zoom_in()
Sheets("Dahboard").Range("o7:t32").Select
ActiveWindow.Zoom = True
End Sub


Sub zoom_out()
Sheets("Dahboard").Range("o7:t32").Select
ActiveWindow.Zoom = False
End Sub


Sub zoom_inT()
Sheets("Dahboard").Range("a1:n32").Select
ActiveWindow.Zoom = True
End Sub


Sub zoom_out_Tb()
Sheets("Dahboard").Range("a1:n32").Select
ActiveWindow.Zoom = False
End Sub

Sub view_change()
If ActiveSheet.Shapes("group 12").Visible = False Then
ActiveSheet.Shapes("group 12").Visible = True
Else:
ActiveSheet.Shapes("group 12").Visible = False
End If
End Sub


![image](https://github.com/ojememary/Phone-City-Hub-Analysis/assets/155962114/c8916da2-4515-4dcb-ab41-235a08e4c805)

  ## Objectives
     ### Best selling product

     Regional Analysis

     Daily Analysis

     Monthly Analysis

   ## Findings

    Iphone sold more in the month of october with a total unit of 195 unit and a total sale of $240,000. it is the most purchased phone.

   ![image](https://github.com/ojememary/Phone-City-Hub-Analysis/assets/155962114/e7865096-f3dd-41d1-b08d-963b9fe35014)


   The east is the highest selling region with a total sale of $290,500

   ![image](https://github.com/ojememary/Phone-City-Hub-Analysis/assets/155962114/184a6fa6-24cb-4add-b2fe-c92917d06835)

   Sunday is the top selling day with a total sale of $196,000

   ![image](https://github.com/ojememary/Phone-City-Hub-Analysis/assets/155962114/0bda3a4b-b60f-4a0c-83f0-5f780e0d2d8a)

   The overall sale for the period of 10 Months is $5,002,500

   ![image](https://github.com/ojememary/Phone-City-Hub-Analysis/assets/155962114/bbfbea24-9d43-48fd-9461-0f7fcb4d08d4)


   ## Recommendation

iPhone Strategy: Launch new models or promotions around October to leverage high interest in iPhone sales.

East Region Strategy: Increase inventory, marketing efforts, and possibly open new stores in the East region to boost sales.

Sunday Sales Strategy:Plan special promotions and enhance the online shopping experience on Sundays to maximize sales opportunities.

Long-Term Sales Strategy: Review trends, invest in loyalty programs, diversify products, and use data analytics for informed decision-making.

Marketing and Promotions: Develop targeted campaigns, especially for the East region, October, and Sundays.

Customer Engagement:Engage with customers via social media and personalized communication, offering exclusive deals to boost loyalty and sales.








  
