```mermaid
flowchart TD

%% =========================
%% Root
%% =========================
BD["Bangladesh Dataset"]

%% =========================
%% Divisions
%% =========================
BD --> D_Dhaka["Dhaka Division"]
BD --> D_Chattogram["Chattogram Division"]
BD --> D_Mymensingh["Mymensingh Division"]
BD --> D_Rajshahi["Rajshahi Division"]

%% =========================
%% Dhaka
%% =========================
D_Dhaka --> Dhaka_Cities["Biggest City"]
D_Dhaka --> Dhaka_Foods["Famous Foods"]
D_Dhaka --> Dhaka_Places["Tourist Place"]
D_Dhaka --> Dhaka_People["Famous People"]

Dhaka_Cities --> DhakaCity["Dhaka City (City)"]
DhakaCity --> DhakaCity_Loc["Location: Dhaka"]

Dhaka_Foods --> KacchiBiryani["Kacchi Biryani (Main Dish)"]
KacchiBiryani --> KacchiBiryani_Loc["Location: Old Dhaka"]

Dhaka_Foods --> MorogPolao["Morog Polao (Main Dish)"]
MorogPolao --> MorogPolao_Loc["Location: Old Dhaka"]

Dhaka_Foods --> Tehari["Tehari (Main Dish)"]
Tehari --> Tehari_Loc["Location: Old Dhaka"]

Dhaka_Foods --> Bakarkhani["Bakarkhani (Snack)"]
Bakarkhani --> Bakarkhani_Loc["Location: Old Dhaka"]

Dhaka_Foods --> Fuchka["Fuchka (Street Food)"]
Fuchka --> Fuchka_Loc["Location: Dhaka"]

Dhaka_Foods --> Halim["Halim (Main Dish)"]
Halim --> Halim_Loc["Location: Dhaka"]

Dhaka_Foods --> Jhalmuri["Jhalmuri (Street Food)"]
Jhalmuri --> Jhalmuri_Loc["Location: Dhaka"]

Dhaka_Foods --> Pitha_Dhaka["Pitha (Sweet)"]
Pitha_Dhaka --> Pitha_Dhaka_Loc["Location: Dhaka"]

Dhaka_Foods --> Borhani["Borhani (Drink)"]
Borhani --> Borhani_Loc["Location: Old Dhaka"]

Dhaka_Foods --> ShahiTukra["Shahi Tukra (Sweet)"]
ShahiTukra --> ShahiTukra_Loc["Location: Old Dhaka"]

Dhaka_Places --> LalbaghFort["Lalbagh Fort (Historical)"]
LalbaghFort --> LalbaghFort_Loc["Location: Dhaka"]

Dhaka_Places --> AhsanManzil["Ahsan Manzil (Historical)"]
AhsanManzil --> AhsanManzil_Loc["Location: Old Dhaka"]

Dhaka_Places --> Parliament["National Parliament House (Historical)"]
Parliament --> Parliament_Loc["Location: Dhaka"]

Dhaka_Places --> ShaheedMinar["Shaheed Minar (Historical)"]
ShaheedMinar --> ShaheedMinar_Loc["Location: Dhaka"]

Dhaka_Places --> StarMosque["Star Mosque (Religious)"]
StarMosque --> StarMosque_Loc["Location: Old Dhaka"]

Dhaka_Places --> DhakeshwariTemple["Dhakeshwari Temple (Religious)"]
DhakeshwariTemple --> DhakeshwariTemple_Loc["Location: Dhaka"]

Dhaka_Places --> Sonargaon["Sonargaon (Historical)"]
Sonargaon --> Sonargaon_Loc["Location: Narayanganj"]

Dhaka_Places --> NationalMuseum["National Museum (Museum)"]
NationalMuseum --> NationalMuseum_Loc["Location: Dhaka"]

Dhaka_People --> Nazrul["Kazi Nazrul Islam (Poet)"]
Nazrul --> Nazrul_Loc["Location: Dhaka"]

Dhaka_People --> Rokeya["Begum Rokeya (Writer)"]
Rokeya --> Rokeya_Loc["Location: Dhaka"]

Dhaka_People --> Zainul["Zainul Abedin (Scholar)"]
Zainul --> Zainul_Loc["Location: Mymensingh"]

Dhaka_People --> Tagore["Rabindranath Tagore (Poet)"]
Tagore --> Tagore_Loc["Location: Dhaka"]

Dhaka_People --> SyedNazrul["Syed Nazrul Islam (Freedom Fighter)"]
SyedNazrul --> SyedNazrul_Loc["Location: Mymensingh"]

Dhaka_People --> Tajuddin["Tajuddin Ahmad (Freedom Fighter)"]
Tajuddin --> Tajuddin_Loc["Location: Gazipur"]

Dhaka_People --> Humayun["Humayun Ahmed (Writer)"]
Humayun --> Humayun_Loc["Location: Mymensingh"]

Dhaka_People --> Jahanara["Jahanara Imam (Writer)"]
Jahanara --> Jahanara_Loc["Location: Dhaka"]

Dhaka_People --> FazlurRahman["Fazlur Rahman Khan (Scholar)"]
FazlurRahman --> FazlurRahman_Loc["Location: Dhaka"]

Dhaka_People --> JagadishBose["Jagadish Chandra Bose (Scholar)"]
JagadishBose --> JagadishBose_Loc["Location: Bikrampur"]

Dhaka_People --> Yunus_Dhaka["Muhammad Yunus (Scholar)"]
Yunus_Dhaka --> Yunus_Dhaka_Loc["Location: Chittagong"]

Dhaka_People --> Taslima_Dhaka["Taslima Nasreen (Writer)"]
Taslima_Dhaka --> Taslima_Dhaka_Loc["Location: Mymensingh"]


%% =========================
%% Chattogram
%% =========================
D_Chattogram --> Chattogram_Cities["Biggest City"]
D_Chattogram --> Chattogram_Foods["Famous Foods"]
D_Chattogram --> Chattogram_Places["Tourist Place"]
D_Chattogram --> Chattogram_People["Famous People"]

Chattogram_Cities --> ChittagongCity["Chittagong City (City)"]
ChittagongCity --> ChittagongCity_Loc["Location: Chattogram"]

Chattogram_Foods --> Mezban["Mezban (Main Dish)"]
Mezban --> Mezban_Loc["Location: Chattogram"]

Chattogram_Foods --> Shutki["Shutki (Main Dish)"]
Shutki --> Shutki_Loc["Location: Chattogram"]

Chattogram_Foods --> KalaBhuna["Kala Bhuna (Main Dish)"]
KalaBhuna --> KalaBhuna_Loc["Location: Chattogram"]

Chattogram_Foods --> Akhni["Akhni (Main Dish)"]
Akhni --> Akhni_Loc["Location: Chattogram"]

Chattogram_Foods --> ChitolMuitha["Chitol Macher Muitha (Main Dish)"]
ChitolMuitha --> ChitolMuitha_Loc["Location: Chattogram"]

Chattogram_Foods --> SorishaIlish["Sorisha Ilish (Main Dish)"]
SorishaIlish --> SorishaIlish_Loc["Location: Chattogram"]

Chattogram_Foods --> BiryaniCTG["Biryani Chittagong Style (Main Dish)"]
BiryaniCTG --> BiryaniCTG_Loc["Location: Chattogram"]

Chattogram_Foods --> Doi_CTG["Doi (Sweet)"]
Doi_CTG --> Doi_CTG_Loc["Location: Chattogram"]

Chattogram_Foods --> Pitha_CTG["Pitha (Sweet)"]
Pitha_CTG --> Pitha_CTG_Loc["Location: Chattogram"]

Chattogram_Places --> CoxBazar["Cox's Bazar (Beach)"]
CoxBazar --> CoxBazar_Loc["Location: Cox's Bazar"]

Chattogram_Places --> SaintMartin["Saint Martin's Island (Nature)"]
SaintMartin --> SaintMartin_Loc["Location: Cox's Bazar"]

Chattogram_Places --> Patenga["Patenga Beach (Beach)"]
Patenga --> Patenga_Loc["Location: Chattogram"]

Chattogram_Places --> FoysLake["Foy's Lake (Nature)"]
FoysLake --> FoysLake_Loc["Location: Chattogram"]

Chattogram_Places --> Himchari["Himchari National Park (Nature)"]
Himchari --> Himchari_Loc["Location: Cox's Bazar"]

Chattogram_Places --> Khaiyachora["Khaiyachora Waterfalls (Nature)"]
Khaiyachora --> Khaiyachora_Loc["Location: Mirsarai"]

Chattogram_Places --> Chandranath["Chandranath Hill (Religious)"]
Chandranath --> Chandranath_Loc["Location: Sitakunda"]

Chattogram_Places --> Alutila["Alutila Cave (Nature)"]
Alutila --> Alutila_Loc["Location: Khagrachari"]

Chattogram_People --> Abed["Fazle Hasan Abed (Leader)"]
Abed --> Abed_Loc["Location: Chattogram"]

Chattogram_People --> Yunus_CTG["Muhammad Yunus (Scholar)"]
Yunus_CTG --> Yunus_CTG_Loc["Location: Chattogram"]

Chattogram_People --> FazlulHuq["A.K. Fazlul Huq (Leader)"]
FazlulHuq --> FazlulHuq_Loc["Location: Barisal"]

Chattogram_People --> SuryaSen["Masterda Surya Sen (Freedom Fighter)"]
SuryaSen --> SuryaSen_Loc["Location: Chattogram"]

Chattogram_People --> Pritilata["Pritilata Waddedar (Martyr)"]
Pritilata --> Pritilata_Loc["Location: Chattogram"]

Chattogram_People --> ZiaurRahman["Major Ziaur Rahman (Freedom Fighter)"]
ZiaurRahman --> ZiaurRahman_Loc["Location: Bogra"]

Chattogram_People --> Mahmudullah["Mahmudullah Riyad (Scholar)"]
Mahmudullah --> Mahmudullah_Loc["Location: Mymensingh"]

Chattogram_People --> Sakib["Sakib Al Hasan (Scholar)"]
Sakib --> Sakib_Loc["Location: Magura"]

Chattogram_People --> NasreenJahan["Nasreen Jahan (Writer)"]
NasreenJahan --> NasreenJahan_Loc["Location: Chattogram"]

Chattogram_People --> SyedMujtaba["Syed Mujtaba Ali (Writer)"]
SyedMujtaba --> SyedMujtaba_Loc["Location: Sylhet"]


%% =========================
%% Mymensingh
%% =========================
D_Mymensingh --> Mymensingh_Cities["Biggest City"]
D_Mymensingh --> Mymensingh_Foods["Famous Foods"]
D_Mymensingh --> Mymensingh_Places["Tourist Place"]
D_Mymensingh --> Mymensingh_People["Famous People"]

Mymensingh_Cities --> MymensinghCity["Mymensingh City (City)"]
MymensinghCity --> MymensinghCity_Loc["Location: Mymensingh"]

Mymensingh_Foods --> Monda["Monda (Sweet)"]
Monda --> Monda_Loc["Location: Mymensingh"]

Mymensingh_Foods --> NakshiPitha["Nakshi Pitha (Sweet)"]
NakshiPitha --> NakshiPitha_Loc["Location: Mymensingh"]

Mymensingh_Foods --> Chitoi["Chitoi Pitha (Snack)"]
Chitoi --> Chitoi_Loc["Location: Mymensingh"]

Mymensingh_Foods --> BhapaPitha["Bhapa Pitha (Sweet)"]
BhapaPitha --> BhapaPitha_Loc["Location: Mymensingh"]

Mymensingh_Foods --> Patishapta["Patishapta (Sweet)"]
Patishapta --> Patishapta_Loc["Location: Mymensingh"]

Mymensingh_Foods --> RutiPitha["Ruti Pitha (Sweet)"]
RutiPitha --> RutiPitha_Loc["Location: Mymensingh"]

Mymensingh_Foods --> PuliPitha["Puli Pitha (Sweet)"]
PuliPitha --> PuliPitha_Loc["Location: Mymensingh"]

Mymensingh_Foods --> DudhPitha["Dudh Pitha (Sweet)"]
DudhPitha --> DudhPitha_Loc["Location: Mymensingh"]

Mymensingh_Foods --> IlishBhapa["Ilish Bhapa (Main Dish)"]
IlishBhapa --> IlishBhapa_Loc["Location: Mymensingh"]

Mymensingh_Places --> Brahmaputra["Brahmaputra River (Nature)"]
Brahmaputra --> Brahmaputra_Loc["Location: Mymensingh"]

Mymensingh_Places --> ShashiLodge["Shashi Lodge (Historical)"]
ShashiLodge --> ShashiLodge_Loc["Location: Mymensingh"]

Mymensingh_Places --> MymensinghMuseum["Mymensingh Museum (Museum)"]
MymensinghMuseum --> MymensinghMuseum_Loc["Location: Mymensingh"]

Mymensingh_Places --> BAU["Bangladesh Agricultural University (Historical)"]
BAU --> BAU_Loc["Location: Mymensingh"]

Mymensingh_Places --> Birishiri["Birishiri (Nature)"]
Birishiri --> Birishiri_Loc["Location: Netrokona"]

Mymensingh_Places --> Madhabkunda["Madhabkunda Waterfall (Nature)"]
Madhabkunda --> Madhabkunda_Loc["Location: Moulvibazar"]

Mymensingh_Places --> Hakaluki["Hakaluki Haor (Nature)"]
Hakaluki --> Hakaluki_Loc["Location: Sylhet"]

Mymensingh_Places --> Tanguar["Tanguar Haor (Nature)"]
Tanguar --> Tanguar_Loc["Location: Sunamganj"]

Mymensingh_People --> Zainul_MYM["Zainul Abedin (Scholar)"]
Zainul_MYM --> Zainul_MYM_Loc["Location: Mymensingh"]

Mymensingh_People --> Humayun_MYM["Humayun Ahmed (Writer)"]
Humayun_MYM --> Humayun_MYM_Loc["Location: Mymensingh"]

Mymensingh_People --> SyedNazrul_MYM["Syed Nazrul Islam (Freedom Fighter)"]
SyedNazrul_MYM --> SyedNazrul_MYM_Loc["Location: Mymensingh"]

Mymensingh_People --> AbuSayeed["Justice Abu Sayeed Chowdhury (Leader)"]
AbuSayeed --> AbuSayeed_Loc["Location: Mymensingh"]

Mymensingh_People --> Shahabuddin["Shahabuddin Ahmed (Leader)"]
Shahabuddin --> Shahabuddin_Loc["Location: Mymensingh"]

Mymensingh_People --> Upendra["Upendra Kishore Roychowdhury (Writer)"]
Upendra --> Upendra_Loc["Location: Mymensingh"]

Mymensingh_People --> Sukumar["Sukumar Ray (Poet)"]
Sukumar --> Sukumar_Loc["Location: Mymensingh"]

Mymensingh_People --> Leela["Leela Majumdar (Writer)"]
Leela --> Leela_Loc["Location: Mymensingh"]

Mymensingh_People --> Nirmalendu["Nirmalendu Goon (Poet)"]
Nirmalendu --> Nirmalendu_Loc["Location: Mymensingh"]

Mymensingh_People --> Helal["Helal Hafiz (Poet)"]
Helal --> Helal_Loc["Location: Mymensingh"]

Mymensingh_People --> Taslima_MYM["Taslima Nasreen (Writer)"]
Taslima_MYM --> Taslima_MYM_Loc["Location: Mymensingh"]

Mymensingh_People --> Mahmudullah_MYM["Mahmudullah Riyad (Scholar)"]
Mahmudullah_MYM --> Mahmudullah_MYM_Loc["Location: Mymensingh"]


%% =========================
%% Rajshahi
%% =========================
D_Rajshahi --> Rajshahi_Cities["Biggest City"]
D_Rajshahi --> Rajshahi_Foods["Famous Foods"]
D_Rajshahi --> Rajshahi_Places["Tourist Place"]
D_Rajshahi --> Rajshahi_People["Famous People"]

Rajshahi_Cities --> RajshahiCity["Rajshahi City (City)"]
RajshahiCity --> RajshahiCity_Loc["Location: Rajshahi"]

Rajshahi_Foods --> MangoDishes["Mango Dishes (Sweet)"]
MangoDishes --> MangoDishes_Loc["Location: Rajshahi"]

Rajshahi_Foods --> Chomchom["Chomchom (Sweet)"]
Chomchom --> Chomchom_Loc["Location: Rajshahi"]

Rajshahi_Foods --> Roshogolla["Roshogolla (Sweet)"]
Roshogolla --> Roshogolla_Loc["Location: Rajshahi"]

Rajshahi_Foods --> Rasmalai["Rasmalai (Sweet)"]
Rasmalai --> Rasmalai_Loc["Location: Rajshahi"]

Rajshahi_Foods --> Kheer["Kheer (Sweet)"]
Kheer --> Kheer_Loc["Location: Rajshahi"]

Rajshahi_Foods --> Doi_Raj["Doi (Sweet)"]
Doi_Raj --> Doi_Raj_Loc["Location: Rajshahi"]

Rajshahi_Foods --> Pantua["Pantua (Sweet)"]
Pantua --> Pantua_Loc["Location: Rajshahi"]

Rajshahi_Foods --> SilkMango["Silk Mango (Sweet)"]
SilkMango --> SilkMango_Loc["Location: Chapainawabganj"]

Rajshahi_Foods --> Langcha["Langcha (Sweet)"]
Langcha --> Langcha_Loc["Location: Rajshahi"]

Rajshahi_Places --> VarendraMuseum["Varendra Research Museum (Museum)"]
VarendraMuseum --> VarendraMuseum_Loc["Location: Rajshahi"]

Rajshahi_Places --> Puthia["Puthia Rajbari Complex (Historical)"]
Puthia --> Puthia_Loc["Location: Puthia"]

Rajshahi_Places --> BaghaMosque["Bagha Shahi Mosque (Religious)"]
BaghaMosque --> BaghaMosque_Loc["Location: Bagha"]

Rajshahi_Places --> MakhdumShrine["Shrine of Hazrat Shah Makhdum (Religious)"]
MakhdumShrine --> MakhdumShrine_Loc["Location: Rajshahi"]

Rajshahi_Places --> Padma["Padma River (Nature)"]
Padma --> Padma_Loc["Location: Rajshahi"]

Rajshahi_Places --> Paharpur["Paharpur Buddhist Monastery (Historical)"]
Paharpur --> Paharpur_Loc["Location: Naogaon"]

Rajshahi_Places --> Kantajew["Kantajew Temple (Religious)"]
Kantajew --> Kantajew_Loc["Location: Dinajpur"]

Rajshahi_Places --> ChhotoSona["Chhoto Sona Mosque (Religious)"]
ChhotoSona --> ChhotoSona_Loc["Location: Chapainawabganj"]

Rajshahi_People --> Zia_Raj["Major Ziaur Rahman (Freedom Fighter)"]
Zia_Raj --> Zia_Raj_Loc["Location: Bogra"]

Rajshahi_People --> AliBogra["Mohammad Ali Bogra (Leader)"]
AliBogra --> AliBogra_Loc["Location: Bogra"]

Rajshahi_People --> Pramatha["Pramatha Chaudhuri (Writer)"]
Pramatha --> Pramatha_Loc["Location: Jessore"]

Rajshahi_People --> Mushfiq["Mushfiqur Rahim (Scholar)"]
Mushfiq --> Mushfiq_Loc["Location: Bogra"]

Rajshahi_People --> Taijul["Taijul Islam (Scholar)"]
Taijul --> Taijul_Loc["Location: Natore"]

Rajshahi_People --> Tunu["Badiuzzaman Tunu (Freedom Fighter)"]
Tunu --> Tunu_Loc["Location: Rajshahi"]

Rajshahi_People --> Tipu["Golam Arif Tipu (Freedom Fighter)"]
Tipu --> Tipu_Loc["Location: Rajshahi"]

Rajshahi_People --> BandeAli["Bande Ali Mia (Poet)"]
BandeAli --> BandeAli_Loc["Location: Rajshahi"]

Rajshahi_People --> Amiya["Amiya Bhushan Majumdar (Writer)"]
Amiya --> Amiya_Loc["Location: Rajshahi"]

Rajshahi_People --> Andrew["Andrew Kishore (Scholar)"]
Andrew --> Andrew_Loc["Location: Rajshahi"]

Rajshahi_People --> Sharmili["Sharmili Ahmed (Scholar)"]
Sharmili --> Sharmili_Loc["Location: Rajshahi"]

Rajshahi_People --> Monjushree["Monjushree Roy (Scholar)"]
Monjushree --> Monjushree_Loc["Location: Rajshahi"]


%% =========================
%% Styling by Type
%% =========================
classDef city fill:#dbeafe,stroke:#1e3a8a,stroke-width:1px;
classDef food fill:#dcfce7,stroke:#166534,stroke-width:1px;
classDef place fill:#fef9c3,stroke:#854d0e,stroke-width:1px;
classDef person fill:#fee2e2,stroke:#991b1b,stroke-width:1px;
classDef category fill:#f3f4f6,stroke:#374151,stroke-width:1px;
classDef division fill:#e0e7ff,stroke:#312e81,stroke-width:2px;

class D_Dhaka,D_Chattogram,D_Mymensingh,D_Rajshahi division;

class Dhaka_Cities,Dhaka_Foods,Dhaka_Places,Dhaka_People category;
class Chattogram_Cities,Chattogram_Foods,Chattogram_Places,Chattogram_People category;
class Mymensingh_Cities,Mymensingh_Foods,Mymensingh_Places,Mymensingh_People category;
class Rajshahi_Cities,Rajshahi_Foods,Rajshahi_Places,Rajshahi_People category;

class DhakaCity,ChittagongCity,MymensinghCity,RajshahiCity city;

class KacchiBiryani,MorogPolao,Tehari,Bakarkhani,Fuchka,Halim,Jhalmuri,Pitha_Dhaka,Borhani,ShahiTukra food;
class Mezban,Shutki,KalaBhuna,Akhni,ChitolMuitha,SorishaIlish,BiryaniCTG,Doi_CTG,Pitha_CTG food;
class Monda,NakshiPitha,Chitoi,BhapaPitha,Patishapta,RutiPitha,PuliPitha,DudhPitha,IlishBhapa food;
class MangoDishes,Chomchom,Roshogolla,Rasmalai,Kheer,Doi_Raj,Pantua,SilkMango,Langcha food;

class LalbaghFort,AhsanManzil,Parliament,ShaheedMinar,StarMosque,DhakeshwariTemple,Sonargaon,NationalMuseum place;
class CoxBazar,SaintMartin,Patenga,FoysLake,Himchari,Khaiyachora,Chandranath,Alutila place;
class Brahmaputra,ShashiLodge,MymensinghMuseum,BAU,Birishiri,Madhabkunda,Hakaluki,Tanguar place;
class VarendraMuseum,Puthia,BaghaMosque,MakhdumShrine,Padma,Paharpur,Kantajew,ChhotoSona place;

class Nazrul,Rokeya,Zainul,Tagore,SyedNazrul,Tajuddin,Humayun,Jahanara,FazlurRahman,JagadishBose,Yunus_Dhaka,Taslima_Dhaka person;
class Abed,Yunus_CTG,FazlulHuq,SuryaSen,Pritilata,ZiaurRahman,Mahmudullah,Sakib,NasreenJahan,SyedMujtaba person;
class Zainul_MYM,Humayun_MYM,SyedNazrul_MYM,AbuSayeed,Shahabuddin,Upendra,Sukumar,Leela,Nirmalendu,Helal,Taslima_MYM,Mahmudullah_MYM person;
class Zia_Raj,AliBogra,Pramatha,Mushfiq,Taijul,Tunu,Tipu,BandeAli,Amiya,Andrew,Sharmili,Monjushree person;
```
