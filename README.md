# Team 4 MIST 4610 Group Project 2

## Team Name
**Group 4**

## Team Members
1. Vivek Murugulla [vcm79503]()
2. Sejal Arora [sejalarora714]()
3. Angie Lin [aangielin]()
4. Alyssa Luangxay [alyssaxlu]()
5. Robert Anthony [ra14858]()

## Dataset Description
Source:

  - This dataset appears to come from an animal shelter in Austin, Texas
  
Purpose:

 - To analyze trends and outcomes for animals in the shelter system, including adoptions, euthanasia, transfers, and returns to owners

Dimensions:

 - Total Rows: 111,360 (each row represents an individual animal outcome)
  

  - Total Columns: 12

Column Descriptions and Data Types:

<img width="728" alt="Screenshot 2025-04-28 at 4 27 14 PM" src="https://github.com/user-attachments/assets/efbe75a0-a2bb-4db1-8d80-3538a6c516f0" />

## Team-Generated Questions and Their Importance

**Question 1:** What is the average age at which each animal receives each type of outcome?

- This question is interesting and important because it gives us a better idea of how animals are treated at different stages of their lives, and what outcomes they’re most likely to face. Analyzing the average age at which animals experience various outcomes, such as adoption, euthanasia, or return to owner, helps us understand patterns in animal care. Economically, knowing the average age tied to different outcomes can help shelters plan their budgets and figure out where to put resources. The data also reflects societal preferences, such as favoring younger animals for adoption or placing a lower value on other animals like livestock. Overall, this question helps shelters guide their choices and shows how communities care for different animals.

**Question 2:** How do euthanasia rates differ between the genders of both cats and dogs?

- This question is insightful because it shows how likely an animal is to be euthanized based on their species and gender. If there’s a big difference between genders, it could suggest critical vulnerability. Analyzing euthanasia rates across different genders of cats and dogs helps us recognize patterns, like whether intact males are at a higher risk compared to neutered or spayed animals. Knowing which groups are most at risk could help shelters prioritize their limited time, space, and marketing resources more efficiently. By identifying specific vulnerable groups, shelters can develop targeted interventions such as promoting spay/neuter programs, tailoring adoption campaigns, or allocating specialized resources to reduce euthanasia rates overall. Furthermore, understanding gender-based trends may encourage broader community education efforts and policies that address the root causes contributing to higher euthanasia risks in certain animal populations.

## Data Manipulations

- Within our data set, the original ‘Age’ column contained inconsistent formats, with entries listed in days, weeks, months, or years (e.g., “15 days,” “8 months,” “1 year”). Given this, Tableau was unable to interpret the ‘age’ column as numerical, making it impossible to conduct quantitative analysis. To address this issue, we imported the data set into Microsoft Excel and created a new column entitled ‘Age in Years’ This column standardized all age entries by converting them into decimal values representing years. For example, an entry saying “45 days” was converted to “0.12” years. We also made sure that this column contained only numeric values without text.
- By transforming the age data in this way, we were able to upload the revised data set into Tableau and successfully use age as a continuous quantitative variable for analysis and visualization.

## Analysis and Results
 A. <img width="902" alt="Screenshot 2025-04-28 at 4 55 20 PM" src="https://github.com/user-attachments/assets/9f0e70da-7db8-4e69-83ad-2cc6aa6f6afd" />
  - First, birds experience all their outcomes at a relatively young age, whether positive or negative. Adoption, return, and transfer typically occur at a young age of 1 to 1.5 years. Similarly, negative outcomes generally occur within 2 years, with most occurring around only 1 year. This pattern suggests that birds are subject to quicker turnover in the shelter system. They seem to be subject to a faster shelter process, but are also vulnerable to early negative outcomes.
  - Next, we see that cats have the youngest average adoption age out of all the animals. They experience relocation and return at an older age, around 4 years. However, on the negative side, cats face their negative outcomes at a young age, with most being at 1-2 years. This pattern of cats experiencing negative outcomes at younger ages may suggest an issue with their adoption or within the shelter system. These issues could be preventing them from reaching the older age when positive outcomes occur. This could be due to health issues, overcrowding, or difficulty fostering older cats.
  - For dogs, the patterns are somewhat similar to those of cats, but they generally experience outcomes at a slightly older age. Adoption occurs at an average age of 1.9 years, which is the oldest adoption age among all the animals. This suggests that dogs spend more time in the shelter before being adopted compared to cats and birds. When it comes to negative outcomes, dogs face euthanasia at the oldest average age out of all the animals, at 4.44 years, and they also experience death and disposal at older ages of around 2.5 years. This suggests older dogs are at a greater risk in the shelter system, and they may face challenges in being adopted, which leads to higher rates of euthanasia as they age.

B. <img width="787" alt="3" src="https://github.com/user-attachments/assets/bc76af23-c7c8-4c29-a8bc-aa5b341fe7d5" />
  - The visualization reveals significant differences in euthanasia rates across species and sex status. Intact males, both among cats and dogs, are euthanized at notably higher rates than their female counterparts and sterilized animals. For both species, neutered males and spayed females have substantially lower euthanasia rates, suggesting that sterilization is associated with better survival outcomes. This pattern is particularly stark for cats, where intact males face an especially high risk. These findings highlight that both gender and reproductive status play a major role in determining the likelihood of euthanasia in shelter environments.
  - The implications of this analysis are critical for animal welfare strategies. Shelters could benefit from prioritizing sterilization programs and targeted marketing or intervention efforts aimed at intact males, who appear to be at the greatest risk. Additionally, educating the public about the behavioral benefits and improved adoption chances for sterilized animals could help lower overall euthanasia rates. Future outreach campaigns might be more effective if they emphasize neutering and focus on male animals, which the data suggest are a particularly vulnerable group.

## Tableau Packaged Workbook
<img width="1470" alt="Screenshot 2025-04-28 at 5 25 45 PM" src="https://github.com/user-attachments/assets/0dbb59cc-2e36-42ec-a5bc-b37258f283c0" />
<img width="1470" alt="Screenshot 2025-04-28 at 5 25 52 PM" src="https://github.com/user-attachments/assets/c895a19b-0a93-4163-b3d8-63b2585e9ac7" />
<img width="1470" alt="Screenshot 2025-04-28 at 5 25 56 PM" src="https://github.com/user-attachments/assets/d36ebd38-5702-4a83-9c96-95bf365f94ea" />









