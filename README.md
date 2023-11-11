# MU Info Hub

A project written in C++ program which can help university to better facilitate and manage the admission process of students.

# Technology used

cpp programming language

# Features

- Details about Metropolitan University(MU)
- Details about all Engi. Departments in MU.
- The project helps the student admission proces.
- Displays Course Details.
- Displays fee structure.

# Screen-shots


<img width="834" alt="A-thumb jpg" src="https://github.com/rahulgit64/Algo-Project/assets/150422604/01640970-147d-4ca5-b683-6a73855f9dd8">
# -
Home


<img width="831" alt="B-about p1 jpg" src="https://github.com/rahulgit64/Algo-Project/assets/150422604/923a777f-8e37-4ab7-bd64-2b99cc4d540a">
# -
About MU p1


<img width="830" alt="B-about p2 jpg" src="https://github.com/rahulgit64/Algo-Project/assets/150422604/c397ee27-28ea-487b-9da5-990e2752c626">
# -
About MU p2


<img width="768" alt="C-adm step p1 jpg" src="https://github.com/rahulgit64/Algo-Project/assets/150422604/22c46318-4069-402e-95af-6cfdebc08d6d">
# -
Admission Step p1


<img width="753" alt="D-adm cost jpg" src="https://github.com/rahulgit64/Algo-Project/assets/150422604/93440d5f-1cd6-4c35-aa10-cd8c5489dbf1">
# -
Admission Costs


<img width="759" alt="E-contact jpg" src="https://github.com/rahulgit64/Algo-Project/assets/150422604/e1a317cc-96d8-424f-b105-3b3262de6267">
# -
MU contact details

# How to use ?

- 1.Download or clone the repository.
- 2.Run the file algo po.cpp with a suitable C/C++ IDE.

 # Code example 

 #include <bits/stdc++.h>
using namespace std;

int main()
{

    std::cout << " " << std::endl;
    std::cout << " " << std::endl;
    std::cout << "                              M   M   U   U     III    N   N   FFFFF   OOO      H   H   U   U   BBBBB\n";
    std::cout << "                              MM MM   U   U      I     NN  N   F      O   O     H   H   U   U   B    B\n";
    std::cout << "                              M M M   U   U      I     N N N   FFF    O   O     HHHHH   U   U   BBBBB\n";
    std::cout << "                              M   M   U   U      I     N  NN   F      O   O     H   H   U   U   B    B\n";
    std::cout << "                              M   M    U U      III    N   N   F       OOO      H   H    U U    BBBBB\n\n";

    std::cout << " " << std::endl;
    std::cout << " " << std::endl;


    std::cout << "                                                     Welcome to MU Info Hub!\n";


    std::cout << "                                                       -------------------" << std::endl;
    std::cout << "                                                 -----------------------------------" << std::endl;
    std::cout << " " << std::endl;
    std::cout << " " << std::endl;
    std::cout << " " << std::endl;

    std::cout << "               1. About MU" << std::endl;
    std::cout << "               2. Admission Steps" << std::endl;
    std::cout << "               3. Admission Cost" << std::endl;
    std::cout << "               4. Contact Us" << std::endl;

    int choice;
    std::cout << "               Enter your choice (1-4): ";
    std::cin >> choice;

    switch (choice)
    {
    case 1:
        std::cout << " " << std::endl;
        std::cout << " " << std::endl;
        std::cout << " " << std::endl;
        std::cout << "About Metropolitan University : " << std::endl;
        std::cout << " " << std::endl;
        std::cout << " " << std::endl;
        std::cout << "Metropolitan University (MU) is a private university in Sylhet and was established in 2003 by a social worker, Toufique Rahman Chowdhury, with the approval of the Ministry of Education under the Private University Act, 1992 (amended in 1998)" << std::endl;
        std::cout<<" "<<std::endl;
        std::cout<<" "<<std::endl;
        std::cout << "Achievements : " << std::endl;

        std::cout << "Metropolitan University has been approved and accredited by the Government of the People's Republic of Bangladesh and University Grants Commission (UGC) of Bangladesh.[1] " << std::endl;
        std::cout << "Besides, Metropolitan University is an Institutional Member of the Association of Management Development Institution in South Asia (AMDISA) and the Member of Association of Management Development Institution in Bangladesh. " << std::endl;
        std::cout << "The Chairman of Accreditation Service of International College (ASIC),[2] Moris Dimok, inspected Metropolitan University on 6 October 2014 and expressed satisfaction by observing " << std::endl;
        std::cout << "the atmosphere of university. On 19 December 2009, Ataul Karim, Vice President (Research), Old Dominion University, US paid a visit to Metropolitan University. Muhammed Zafar Iqbal, " << std::endl;
        std::cout << "Head of the Department of Computer Science & Technology of Shahjalal University of Science and Technology (SUST), Sylhet also visited the Project Fair of Metropolitan University.[3] " << std::endl;
        std::cout << "The university has four schools and six departments. These are:[4][5] " << std::endl;
        std::cout<<" "<<std::endl;
        std::cout<<" "<<std::endl;
        std::cout << "List of vice-chancellors : " << std::endl;
        std::cout << "Prof. Dr. Md. Saleh Uddin ( EX ) " << std::endl;
        std::cout << "Prof. Dr. Mohammad Jahirul Hoque ( PRESENT) " << std::endl;
        std::cout<<" "<<std::endl;
        std::cout<<" "<<std::endl;
        std::cout << "School of Science & Technology : " << std::endl;
        std::cout << "There are three engineering departments. Both departments are currently offering B.Sc.(Engg.) degree. The dean is Md. Nazrul Haque. " << std::endl;
        std::cout<<" "<<std::endl;
        std::cout<<" "<<std::endl;
        std::cout << "Departments " << std::endl;
        std::cout << "Department of Computer Science & Engineering (CSE) " << std::endl;
        std::cout << "Department of Software Engineering (SE) " << std::endl;
        std::cout << "Department of Electrical & Electronics Engineering (EEE) " << std::endl;

        break;
    case 2:
        std::cout << " " << std::endl;
        std::cout << " " << std::endl;
        std::cout << " " << std::endl;
        std::cout << "Admission Steps:" << std::endl;
        std::cout << " " << std::endl;
        std::cout << " " << std::endl;
        std::cout << " Students who have passed SSC and HSC or any equivalent " << std::endl;
        std::cout << " examination with at least two 2nd divisions or minimum GPA " << std::endl;
        std::cout << " 2.5 in each (in the scale of 5) may apply for admission. " << std::endl;
        std::cout << " Alternatively, students who have minimum GPA 2.00 in any " << std::endl;
        std::cout << " one of SSC or HSC and a total of GPA 6.00 may also apply. " << std::endl;
        std::cout << " " << std::endl;

        break;
    case 3:
        std::cout << " " << std::endl;
        std::cout << " " << std::endl;
        std::cout << " " << std::endl;
        std::cout << "Admission cost in others departments : " << std::endl;
        std::cout << " " << std::endl;
        std::cout << " " << std::endl;

        std::cout << " CSE / Software engi. / EEE  " << std::endl;
        std::cout << " Total fee : 4,05,200/= " << std::endl;
        std::cout << " Tenure: 4 years " << std::endl;
        std::cout << " Admission fee : 20000/= " << std::endl;
        std::cout << " Semister fee : 15150/=(Total 8 semister) " << std::endl;
        std::cout << " Monthly activity fee : 500/= " << std::endl;
        std::cout << " Monthly fee : 5000/= " << std::endl;
        std::cout << " " << std::endl;
        std::cout << " " << std::endl;
        std::cout << " Total cost after discount for SSC+HSC result : " << std::endl;
        std::cout << " " << std::endl;
        std::cout << " " << std::endl;
        std::cout << " GPA 10.00 (2 Golden): 100% OFF, Total: 1,65,000/- " << std::endl;
        std::cout << " GPA 10.00 (1 Golden): 60% OFF, Total: 261,200/- " << std::endl;
        std::cout << " GPA 10.00 : 40% OFF. Total: 309,200/- " << std::endl;
        std::cout << " GPA 9.00 : 30% OFF, Total: 333,200/- " << std::endl;
        std::cout << " GPA 8.00 : 15% OFF, Total: 369,200/- " << std::endl;
        std::cout << " GPA 7.00 : 10% OFF, 381,200/- " << std::endl;
        std::cout << " GPA 6.00 : 5% OFF, 393,200/- " << std::endl;
        std::cout << " " << std::endl;
        std::cout << " " << std::endl;
        std::cout << " Female students: 	20% OFF " << std::endl;


        break;
    case 4:
        std::cout << " " << std::endl;
        std::cout << " " << std::endl;
        std::cout << " " << std::endl;
        std::cout << "Contact Us:" << std::endl;

        std::cout << " " << std::endl;
        std::cout << " " << std::endl;
        std::cout << "01610932939, 01313050044, 01313050066 " << std::endl;
        std::cout << " " << std::endl;
        std::cout << " " << std::endl;
        std::cout << "Email: info@metrouni.edu.bd " << std::endl;
        std::cout << "Web: http://www.metrouni.edu.bd " << std::endl;
        std::cout << " " << std::endl;
        std::cout << " " << std::endl;
        std::cout << "Campus Address:  " << std::endl;
        std::cout << " " << std::endl;
        std::cout << " " << std::endl;
        std::cout << "Metropolitan University Bateshwar, Sylhet 3103 Bangladesh " << std::endl;
        std::cout << " " << std::endl;
        std::cout << "Map:  https://goo.gl/maps/YGGUoqev9AKCKVFS9 " << std::endl;


        break;
    default:
        std::cout << " " << std::endl;
        std::cout << " " << std::endl;
        std::cout << " " << std::endl;
        std::cout << "Invalid choice. Please select a valid option (1-4)." << std::endl;
        std::cout << " " << std::endl;
        std::cout << " " << std::endl;
        std::cout << " " << std::endl;
        break;
    }

    return 0;
}

# Credit

@rahulgit64


