```mermaid
flowchart TD

%% =========================
%% Root Node
%% =========================
BD["🇧🇩 Bangladesh Cultural Heritage"]

%% =========================
%% Division Nodes
%% =========================
BD --> D_Dhaka["📍 Dhaka Division"]
BD --> D_Chattogram["📍 Chattogram Division"]
BD --> D_Mymensingh["📍 Mymensingh Division"]
BD --> D_Rajshahi["📍 Rajshahi Division"]

%% =========================
%% DHAKA DIVISION
%% =========================

%% --- Category Nodes ---
D_Dhaka --> Dhaka_Cities["🏙️ Cities"]
D_Dhaka --> Dhaka_Foods["🍽️ Foods"]
D_Dhaka --> Dhaka_Places["🏛️ Places"]
D_Dhaka --> Dhaka_People["👤 People"]

%% --- Cities ---
Dhaka_Cities --> DhakaCity["Dhaka City"]
DhakaCity --> DhakaCity_Info["Capital | 10M+ population<br/>Economic & admin center"]

%% --- Foods ---
Dhaka_Foods --> KacchiBiryani["Kacchi Biryani"]
KacchiBiryani --> KacchiBiryani_Info["Main Dish | Old Dhaka<br/>Fragrant rice with mutton"]

Dhaka_Foods --> MorogPolao["Morog Polao"]
MorogPolao --> MorogPolao_Info["Main Dish | Old Dhaka<br/>Aromatic chicken rice"]

Dhaka_Foods --> Tehari["Tehari"]
Tehari --> Tehari_Info["Main Dish | Old Dhaka<br/>Spicy beef in mustard oil"]

Dhaka_Foods --> Bakarkhani["Bakarkhani"]
Bakarkhani --> Bakarkhani_Info["Snack | Old Dhaka<br/>Traditional flatbread"]

Dhaka_Foods --> Fuchka["Fuchka"]
Fuchka --> Fuchka_Info["Street Food | Dhaka<br/>#1 street food nationwide"]

Dhaka_Foods --> Halim["Halim"]
Halim --> Halim_Info["Main Dish | Dhaka<br/>Lentil soup with meat"]

Dhaka_Foods --> Jhalmuri["Jhalmuri"]
Jhalmuri --> Jhalmuri_Info["Street Food | Dhaka<br/>Spiced puffed rice"]

Dhaka_Foods --> Pitha_Dhaka["Pitha"]
Pitha_Dhaka --> Pitha_Dhaka_Info["Sweet | Dhaka<br/>Winter rice cakes"]

Dhaka_Foods --> Borhani["Borhani"]
Borhani --> Borhani_Info["Drink | Old Dhaka<br/>Spiced yogurt drink"]

Dhaka_Foods --> ShahiTukra["Shahi Tukra"]
ShahiTukra --> ShahiTukra_Info["Sweet | Old Dhaka<br/>Mughal royal dessert"]

%% --- Places ---
Dhaka_Places --> LalbaghFort["Lalbagh Fort"]
LalbaghFort --> LalbaghFort_Info["Historical | Dhaka<br/>17th century Mughal fort"]

Dhaka_Places --> AhsanManzil["Ahsan Manzil"]
AhsanManzil --> AhsanManzil_Info["Historical | Old Dhaka<br/>Pink Palace of Nawab"]

Dhaka_Places --> Parliament["National Parliament"]
Parliament --> Parliament_Info["Historical | Dhaka<br/>Louis Kahn masterpiece"]

Dhaka_Places --> ShaheedMinar["Shaheed Minar"]
ShaheedMinar --> ShaheedMinar_Info["Historical | Dhaka<br/>Language movement symbol"]

Dhaka_Places --> StarMosque["Star Mosque"]
StarMosque --> StarMosque_Info["Religious | Old Dhaka<br/>Ornate tile decorations"]

Dhaka_Places --> DhakeshwariTemple["Dhakeshwari Temple"]
DhakeshwariTemple --> DhakeshwariTemple_Info["Religious | Dhaka<br/>National Hindu temple"]

Dhaka_Places --> Sonargaon["Sonargaon"]
Sonargaon --> Sonargaon_Info["Historical | Narayanganj<br/>Ancient capital of Bengal"]

Dhaka_Places --> NationalMuseum["National Museum"]
NationalMuseum --> NationalMuseum_Info["Museum | Dhaka<br/>Largest museum collection"]

%% --- People ---
Dhaka_People --> Nazrul["Kazi Nazrul Islam"]
Nazrul --> Nazrul_Info["Poet | National Poet<br/>Revolutionary poetry"]

Dhaka_People --> Rokeya["Begum Rokeya"]
Rokeya --> Rokeya_Info["Writer | Pioneer feminist<br/>Women's education advocate"]

Dhaka_People --> Zainul["Zainul Abedin"]
Zainul --> Zainul_Info["Scholar | Mymensingh<br/>Founder modern BD art"]

Dhaka_People --> Tagore["Rabindranath Tagore"]
Tagore --> Tagore_Info["Poet | Nobel Laureate<br/>National anthem composer"]

Dhaka_People --> SyedNazrul["Syed Nazrul Islam"]
SyedNazrul --> SyedNazrul_Info["Freedom Fighter | Mymensingh<br/>Acting President 1971"]

Dhaka_People --> Tajuddin["Tajuddin Ahmad"]
Tajuddin --> Tajuddin_Info["Freedom Fighter | Gazipur<br/>First Prime Minister"]

Dhaka_People --> Humayun["Humayun Ahmed"]
Humayun --> Humayun_Info["Writer | Mymensingh<br/>Most popular novelist"]

Dhaka_People --> Jahanara["Jahanara Imam"]
Jahanara --> Jahanara_Info["Writer | Shaheed Janani<br/>War crimes activist"]

Dhaka_People --> FazlurKhan["Fazlur Rahman Khan"]
FazlurKhan --> FazlurKhan_Info["Scholar | Structural engineer<br/>Tubular design pioneer"]

Dhaka_People --> JagadishBose["Jagadish C. Bose"]
JagadishBose --> JagadishBose_Info["Scholar | Bikrampur<br/>Pioneer physicist & biologist"]

Dhaka_People --> Yunus_Dhaka["Muhammad Yunus"]
Yunus_Dhaka --> Yunus_Dhaka_Info["Scholar | Chittagong<br/>Nobel laureate | Microcredit"]

Dhaka_People --> Taslima_Dhaka["Taslima Nasreen"]
Taslima_Dhaka --> Taslima_Dhaka_Info["Writer | Mymensingh<br/>Feminist & rights activist"]


%% =========================
%% CHATTOGRAM DIVISION
%% =========================

%% --- Category Nodes ---
D_Chattogram --> Chattogram_Cities["🏙️ Cities"]
D_Chattogram --> Chattogram_Foods["🍽️ Foods"]
D_Chattogram --> Chattogram_Places["🏛️ Places"]
D_Chattogram --> Chattogram_People["👤 People"]

%% --- Cities ---
Chattogram_Cities --> ChittagongCity["Chittagong City"]
ChittagongCity --> ChittagongCity_Info["Port City | 3.2M population<br/>Commercial hub"]

%% --- Foods ---
Chattogram_Foods --> Mezban["Mezban"]
Mezban --> Mezban_Info["Main Dish | Chattogram<br/>Ceremonial beef curry"]

Chattogram_Foods --> Shutki["Shutki"]
Shutki --> Shutki_Info["Main Dish | Chattogram<br/>Dried fish curry"]

Chattogram_Foods --> KalaBhuna["Kala Bhuna"]
KalaBhuna --> KalaBhuna_Info["Main Dish | Chattogram<br/>Slow-cooked spicy beef"]

Chattogram_Foods --> Akhni["Akhni"]
Akhni --> Akhni_Info["Main Dish | Chattogram<br/>Fragrant rice with spices"]

Chattogram_Foods --> ChitolMuitha["Chitol Macher Muitha"]
ChitolMuitha --> ChitolMuitha_Info["Main Dish | Chattogram<br/>Fish ball curry"]

Chattogram_Foods --> SorishaIlish["Sorisha Ilish"]
SorishaIlish --> SorishaIlish_Info["Main Dish | Chattogram<br/>Hilsa in mustard sauce"]

Chattogram_Foods --> BiryaniCTG["Biryani CTG Style"]
BiryaniCTG --> BiryaniCTG_Info["Main Dish | Chattogram<br/>Regional spice variation"]

Chattogram_Foods --> Doi_CTG["Doi"]
Doi_CTG --> Doi_CTG_Info["Sweet | Chattogram<br/>Thick sweetened yogurt"]

Chattogram_Foods --> Pitha_CTG["Pitha"]
Pitha_CTG --> Pitha_CTG_Info["Sweet | Chattogram<br/>Traditional winter cakes"]

%% --- Places ---
Chattogram_Places --> CoxBazar["Cox's Bazar"]
CoxBazar --> CoxBazar_Info["Beach | 150km long<br/>World's longest beach"]

Chattogram_Places --> SaintMartin["Saint Martin's Island"]
SaintMartin --> SaintMartin_Info["Nature | Cox's Bazar<br/>Only coral island"]

Chattogram_Places --> Patenga["Patenga Beach"]
Patenga --> Patenga_Info["Beach | Chattogram<br/>Stunning sunset views"]

Chattogram_Places --> FoysLake["Foy's Lake"]
FoysLake --> FoysLake_Info["Nature | Chattogram<br/>320 acre recreation spot"]

Chattogram_Places --> Himchari["Himchari Park"]
Himchari --> Himchari_Info["Nature | Cox's Bazar<br/>Protected forest & falls"]

Chattogram_Places --> Khaiyachora["Khaiyachora Falls"]
Khaiyachora --> Khaiyachora_Info["Nature | Mirsarai<br/>Largest waterfall in BD"]

Chattogram_Places --> Chandranath["Chandranath Hill"]
Chandranath --> Chandranath_Info["Religious | Sitakunda<br/>Sacred hilltop temple"]

Chattogram_Places --> Alutila["Alutila Cave"]
Alutila --> Alutila_Info["Nature | Khagrachari<br/>100m cave system"]

%% --- People ---
Chattogram_People --> Abed["Fazle Hasan Abed"]
Abed --> Abed_Info["Leader | Chattogram<br/>BRAC founder"]

Chattogram_People --> Yunus_CTG["Muhammad Yunus"]
Yunus_CTG --> Yunus_CTG_Info["Scholar | Chattogram<br/>Grameen Bank founder"]

Chattogram_People --> FazlulHuq["A.K. Fazlul Huq"]
FazlulHuq --> FazlulHuq_Info["Leader | Barisal<br/>Sher-e-Bangla"]

Chattogram_People --> SuryaSen["Masterda Surya Sen"]
SuryaSen --> SuryaSen_Info["Freedom Fighter | CTG<br/>Armory Raid leader 1930"]

Chattogram_People --> Pritilata["Pritilata Waddedar"]
Pritilata --> Pritilata_Info["Martyr | Chattogram<br/>First female martyr"]

Chattogram_People --> ZiaurRahman["Major Ziaur Rahman"]
ZiaurRahman --> ZiaurRahman_Info["Freedom Fighter | Bogra<br/>BNP founder | President"]

Chattogram_People --> Mahmudullah["Mahmudullah Riyad"]
Mahmudullah --> Mahmudullah_Info["Scholar | Mymensingh<br/>Cricket captain"]

Chattogram_People --> Shakib["Shakib Al Hasan"]
Shakib --> Shakib_Info["Scholar | Magura<br/>World #1 all-rounder"]

Chattogram_People --> NasreenJahan["Nasreen Jahan"]
NasreenJahan --> NasreenJahan_Info["Writer | Chattogram<br/>Renowned novelist"]

Chattogram_People --> SyedMujtaba["Syed Mujtaba Ali"]
SyedMujtaba --> SyedMujtaba_Info["Writer | Sylhet<br/>Travel & humor writer"]


%% =========================
%% MYMENSINGH DIVISION
%% =========================

%% --- Category Nodes ---
D_Mymensingh --> Mymensingh_Cities["🏙️ Cities"]
D_Mymensingh --> Mymensingh_Foods["🍽️ Foods"]
D_Mymensingh --> Mymensingh_Places["🏛️ Places"]
D_Mymensingh --> Mymensingh_People["👤 People"]

%% --- Cities ---
Mymensingh_Cities --> MymensinghCity["Mymensingh City"]
MymensinghCity --> MymensinghCity_Info["Metro | 389K population<br/>Educational hub"]

%% --- Foods ---
Mymensingh_Foods --> Monda["Monda"]
Monda --> Monda_Info["Sweet | Mymensingh<br/>Rice flour & molasses ball"]

Mymensingh_Foods --> NakshiPitha["Nakshi Pitha"]
NakshiPitha --> NakshiPitha_Info["Sweet | Mymensingh<br/>Decorative rice art cake"]

Mymensingh_Foods --> Chitoi["Chitoi Pitha"]
Chitoi --> Chitoi_Info["Snack | Mymensingh<br/>Steamed rice pancakes"]

Mymensingh_Foods --> BhapaPitha["Bhapa Pitha"]
BhapaPitha --> BhapaPitha_Info["Sweet | Mymensingh<br/>Coconut-jaggery filled"]

Mymensingh_Foods --> Patishapta["Patishapta"]
Patishapta --> Patishapta_Info["Sweet | Mymensingh<br/>Thin sweet crepes"]

Mymensingh_Foods --> RutiPitha["Ruti Pitha"]
RutiPitha --> RutiPitha_Info["Sweet | Mymensingh<br/>Fried crispy bread"]

Mymensingh_Foods --> PuliPitha["Puli Pitha"]
PuliPitha --> PuliPitha_Info["Sweet | Mymensingh<br/>Dumpling-shaped cakes"]

Mymensingh_Foods --> DudhPitha["Dudh Pitha"]
DudhPitha --> DudhPitha_Info["Sweet | Mymensingh<br/>Rice cakes in sweet milk"]

Mymensingh_Foods --> IlishBhapa["Ilish Bhapa"]
IlishBhapa --> IlishBhapa_Info["Main Dish | Mymensingh<br/>Steamed hilsa fish"]

%% --- Places ---
Mymensingh_Places --> Brahmaputra["Brahmaputra River"]
Brahmaputra --> Brahmaputra_Info["Nature | Mymensingh<br/>Mighty scenic waterway"]

Mymensingh_Places --> ShashiLodge["Shashi Lodge"]
ShashiLodge --> ShashiLodge_Info["Historical | Mymensingh<br/>Zamindar palace heritage"]

Mymensingh_Places --> MymensinghMuseum["Mymensingh Museum"]
MymensinghMuseum --> MymensinghMuseum_Info["Museum | Mymensingh<br/>Regional artifacts"]

Mymensingh_Places --> BAU["BAU University"]
BAU --> BAU_Info["Historical | Mymensingh<br/>Premier agri institution"]

Mymensingh_Places --> Birishiri["Birishiri"]
Birishiri --> Birishiri_Info["Nature | Netrokona<br/>Hills & Garo culture"]

Mymensingh_Places --> Madhabkunda["Madhabkunda Falls"]
Madhabkunda --> Madhabkunda_Info["Nature | Moulvibazar<br/>Spectacular waterfall"]

Mymensingh_Places --> Hakaluki["Hakaluki Haor"]
Hakaluki --> Hakaluki_Info["Nature | Sylhet<br/>Largest wetland ecosystem"]

Mymensingh_Places --> Tanguar["Tanguar Haor"]
Tanguar --> Tanguar_Info["Nature | Sunamganj<br/>Ramsar biodiversity site"]

%% --- People ---
Mymensingh_People --> Zainul_MYM["Zainul Abedin"]
Zainul_MYM --> Zainul_MYM_Info["Scholar | Shilpacharya<br/>Master painter"]

Mymensingh_People --> Humayun_MYM["Humayun Ahmed"]
Humayun_MYM --> Humayun_MYM_Info["Writer | Mymensingh<br/>Beloved novelist & filmmaker"]

Mymensingh_People --> SyedNazrul_MYM["Syed Nazrul Islam"]
SyedNazrul_MYM --> SyedNazrul_MYM_Info["Freedom Fighter<br/>Liberation War leader"]

Mymensingh_People --> AbuSayeed["Abu Sayeed Chowdhury"]
AbuSayeed --> AbuSayeed_Info["Leader | Mymensingh<br/>First President of BD"]

Mymensingh_People --> Shahabuddin["Shahabuddin Ahmed"]
Shahabuddin --> Shahabuddin_Info["Leader | Mymensingh<br/>President & Chief Justice"]

Mymensingh_People --> Upendra["Upendra K. Roy"]
Upendra --> Upendra_Info["Writer | Mymensingh<br/>Pioneer printer & author"]

Mymensingh_People --> Sukumar["Sukumar Ray"]
Sukumar --> Sukumar_Info["Poet | Mymensingh<br/>Legendary children's poet"]

Mymensingh_People --> Leela["Leela Majumdar"]
Leela --> Leela_Info["Writer | Mymensingh<br/>Beloved children's author"]

Mymensingh_People --> Nirmalendu["Nirmalendu Goon"]
Nirmalendu --> Nirmalendu_Info["Poet | Mymensingh<br/>Contemporary Bengali poet"]

Mymensingh_People --> Helal["Helal Hafiz"]
Helal --> Helal_Info["Poet | Mymensingh<br/>1970s generation poet"]

Mymensingh_People --> Taslima_MYM["Taslima Nasreen"]
Taslima_MYM --> Taslima_MYM_Info["Writer | Mymensingh<br/>Feminist activist"]

Mymensingh_People --> Mahmudullah_MYM["Mahmudullah Riyad"]
Mahmudullah_MYM --> Mahmudullah_MYM_Info["Scholar | Cricketer<br/>World Cup centurion"]


%% =========================
%% RAJSHAHI DIVISION
%% =========================

%% --- Category Nodes ---
D_Rajshahi --> Rajshahi_Cities["🏙️ Cities"]
D_Rajshahi --> Rajshahi_Foods["🍽️ Foods"]
D_Rajshahi --> Rajshahi_Places["🏛️ Places"]
D_Rajshahi --> Rajshahi_People["👤 People"]

%% --- Cities ---
Rajshahi_Cities --> RajshahiCity["Rajshahi City"]
RajshahiCity --> RajshahiCity_Info["Metro | 760K population<br/>Silk & mango capital"]

%% --- Foods ---
Rajshahi_Foods --> MangoDishes["Mango Dishes"]
MangoDishes --> MangoDishes_Info["Sweet | Rajshahi<br/>Finest mangoes in BD"]

Rajshahi_Foods --> Chomchom["Chomchom"]
Chomchom --> Chomchom_Info["Sweet | Rajshahi<br/>Oval milk sweet"]

Rajshahi_Foods --> Roshogolla["Roshogolla"]
Roshogolla --> Roshogolla_Info["Sweet | Rajshahi<br/>Spongy cheese balls"]

Rajshahi_Foods --> Rasmalai["Rasmalai"]
Rasmalai --> Rasmalai_Info["Sweet | Rajshahi<br/>Soft cheese in milk"]

Rajshahi_Foods --> Kheer["Kheer"]
Kheer --> Kheer_Info["Sweet | Rajshahi<br/>Rice pudding dessert"]

Rajshahi_Foods --> Doi_Raj["Doi"]
Doi_Raj --> Doi_Raj_Info["Sweet | Rajshahi<br/>Clay pot yogurt"]

Rajshahi_Foods --> Pantua["Pantua"]
Pantua --> Pantua_Info["Sweet | Rajshahi<br/>Fried milk sweet"]

Rajshahi_Foods --> SilkMango["Silk Mango"]
SilkMango --> SilkMango_Info["Sweet | Chapainawabganj<br/>World-famous variety"]

Rajshahi_Foods --> Langcha["Langcha"]
Langcha --> Langcha_Info["Sweet | Rajshahi<br/>Cylindrical fried sweet"]

%% --- Places ---
Rajshahi_Places --> VarendraMuseum["Varendra Museum"]
VarendraMuseum --> VarendraMuseum_Info["Museum | Rajshahi<br/>First museum BD 1910"]

Rajshahi_Places --> Puthia["Puthia Rajbari"]
Puthia --> Puthia_Info["Historical | Puthia<br/>Palace & temple complex"]

Rajshahi_Places --> BaghaMosque["Bagha Mosque"]
BaghaMosque --> BaghaMosque_Info["Religious | Bagha<br/>16th century terracotta"]

Rajshahi_Places --> MakhdumShrine["Shah Makhdum Shrine"]
MakhdumShrine --> MakhdumShrine_Info["Religious | Rajshahi<br/>Pilgrimage on Padma"]

Rajshahi_Places --> Padma["Padma River"]
Padma --> Padma_Info["Nature | Rajshahi<br/>Mighty river sunset views"]

Rajshahi_Places --> Paharpur["Paharpur Monastery"]
Paharpur --> Paharpur_Info["Historical | Naogaon<br/>UNESCO World Heritage"]

Rajshahi_Places --> Kantajew["Kantajew Temple"]
Kantajew --> Kantajew_Info["Religious | Dinajpur<br/>18th century terracotta"]

Rajshahi_Places --> ChhotoSona["Chhoto Sona Mosque"]
ChhotoSona --> ChhotoSona_Info["Religious | Chapainawabganj<br/>15th century golden mosque"]

%% --- People ---
Rajshahi_People --> Zia_Raj["Major Ziaur Rahman"]
Zia_Raj --> Zia_Raj_Info["Freedom Fighter | Bogra<br/>Declared independence"]

Rajshahi_People --> AliBogra["Mohammad Ali Bogra"]
AliBogra --> AliBogra_Info["Leader | Bogra<br/>3rd PM of Pakistan"]

Rajshahi_People --> Pramatha["Pramatha Chaudhuri"]
Pramatha --> Pramatha_Info["Writer | Jessore<br/>Modernized Bengali prose"]

Rajshahi_People --> Mushfiq["Mushfiqur Rahim"]
Mushfiq --> Mushfiq_Info["Scholar | Bogra<br/>Wicketkeeper-batsman"]

Rajshahi_People --> Taijul["Taijul Islam"]
Taijul --> Taijul_Info["Scholar | Natore<br/>Leading spin bowler"]

Rajshahi_People --> Tunu["Badiuzzaman Tunu"]
Tunu --> Tunu_Info["Freedom Fighter | Rajshahi<br/>Liberation War hero"]

Rajshahi_People --> Tipu["Golam Arif Tipu"]
Tipu --> Tipu_Info["Freedom Fighter | Rajshahi<br/>Language movement veteran"]

Rajshahi_People --> BandeAli["Bande Ali Mia"]
BandeAli --> BandeAli_Info["Poet | Rajshahi<br/>Rural folk tradition"]

Rajshahi_People --> Amiya["Amiya B. Majumdar"]
Amiya --> Amiya_Info["Writer | Rajshahi<br/>Bengali novelist"]

Rajshahi_People --> Andrew["Andrew Kishore"]
Andrew --> Andrew_Info["Scholar | Rajshahi<br/>Legendary playback singer"]

Rajshahi_People --> Sharmili["Sharmili Ahmed"]
Sharmili --> Sharmili_Info["Scholar | Rajshahi<br/>Acclaimed actress"]

Rajshahi_People --> Monjushree["Monjushree Roy"]
Monjushree --> Monjushree_Info["Scholar | Rajshahi<br/>Classical music artist"]


%% =========================
%% STYLING CLASSES
%% =========================

%% Root & Divisions
classDef rootStyle fill:#1e40af,stroke:#1e3a8a,stroke-width:3px,color:#fff,font-weight:bold,font-size:16px;
classDef divisionStyle fill:#4f46e5,stroke:#312e81,stroke-width:2.5px,color:#fff,font-weight:bold;

%% Categories
classDef categoryStyle fill:#8b5cf6,stroke:#5b21b6,stroke-width:2px,color:#fff,font-weight:bold;

%% Content Types
classDef cityStyle fill:#06b6d4,stroke:#0e7490,stroke-width:2px,color:#fff;
classDef foodStyle fill:#10b981,stroke:#047857,stroke-width:2px,color:#fff;
classDef placeStyle fill:#f59e0b,stroke:#b45309,stroke-width:2px,color:#fff;
classDef personStyle fill:#ef4444,stroke:#b91c1c,stroke-width:2px,color:#fff;

%% Info Nodes
classDef infoStyle fill:#f3f4f6,stroke:#6b7280,stroke-width:1px,color:#111827,font-size:11px;

%% Apply Styles
class BD rootStyle;
class D_Dhaka,D_Chattogram,D_Mymensingh,D_Rajshahi divisionStyle;

class Dhaka_Cities,Dhaka_Foods,Dhaka_Places,Dhaka_People categoryStyle;
class Chattogram_Cities,Chattogram_Foods,Chattogram_Places,Chattogram_People categoryStyle;
class Mymensingh_Cities,Mymensingh_Foods,Mymensingh_Places,Mymensingh_People categoryStyle;
class Rajshahi_Cities,Rajshahi_Foods,Rajshahi_Places,Rajshahi_People categoryStyle;

class DhakaCity,ChittagongCity,MymensinghCity,RajshahiCity cityStyle;

class KacchiBiryani,MorogPolao,Tehari,Bakarkhani,Fuchka,Halim,Jhalmuri,Pitha_Dhaka,Borhani,ShahiTukra foodStyle;
class Mezban,Shutki,KalaBhuna,Akhni,ChitolMuitha,SorishaIlish,BiryaniCTG,Doi_CTG,Pitha_CTG foodStyle;
class Monda,NakshiPitha,Chitoi,BhapaPitha,Patishapta,RutiPitha,PuliPitha,DudhPitha,IlishBhapa foodStyle;
class MangoDishes,Chomchom,Roshogolla,Rasmalai,Kheer,Doi_Raj,Pantua,SilkMango,Langcha foodStyle;

class LalbaghFort,AhsanManzil,Parliament,ShaheedMinar,StarMosque,DhakeshwariTemple,Sonargaon,NationalMuseum placeStyle;
class CoxBazar,SaintMartin,Patenga,FoysLake,Himchari,Khaiyachora,Chandranath,Alutila placeStyle;
class Brahmaputra,ShashiLodge,MymensinghMuseum,BAU,Birishiri,Madhabkunda,Hakaluki,Tanguar placeStyle;
class VarendraMuseum,Puthia,BaghaMosque,MakhdumShrine,Padma,Paharpur,Kantajew,ChhotoSona placeStyle;

class Nazrul,Rokeya,Zainul,Tagore,SyedNazrul,Tajuddin,Humayun,Jahanara,FazlurKhan,JagadishBose,Yunus_Dhaka,Taslima_Dhaka personStyle;
class Abed,Yunus_CTG,FazlulHuq,SuryaSen,Pritilata,ZiaurRahman,Mahmudullah,Shakib,NasreenJahan,SyedMujtaba personStyle;
class Zainul_MYM,Humayun_MYM,SyedNazrul_MYM,AbuSayeed,Shahabuddin,Upendra,Sukumar,Leela,Nirmalendu,Helal,Taslima_MYM,Mahmudullah_MYM personStyle;
class Zia_Raj,AliBogra,Pramatha,Mushfiq,Taijul,Tunu,Tipu,BandeAli,Amiya,Andrew,Sharmili,Monjushree personStyle;

class DhakaCity_Info,KacchiBiryani_Info,MorogPolao_Info,Tehari_Info,Bakarkhani_Info,Fuchka_Info,Halim_Info,Jhalmuri_Info,Pitha_Dhaka_Info,Borhani_Info,ShahiTukra_Info infoStyle;
class LalbaghFort_Info,AhsanManzil_Info,Parliament_Info,ShaheedMinar_Info,StarMosque_Info,DhakeshwariTemple_Info,Sonargaon_Info,NationalMuseum_Info infoStyle;
class Nazrul_Info,Rokeya_Info,Zainul_Info,Tagore_Info,SyedNazrul_Info,Tajuddin_Info,Humayun_Info,Jahanara_Info,FazlurKhan_Info,JagadishBose_Info,Yunus_Dhaka_Info,Taslima_Dhaka_Info infoStyle;

class ChittagongCity_Info,Mezban_Info,Shutki_Info,KalaBhuna_Info,Akhni_Info,ChitolMuitha_Info,SorishaIlish_Info,BiryaniCTG_Info,Doi_CTG_Info,Pitha_CTG_Info infoStyle;
class CoxBazar_Info,SaintMartin_Info,Patenga_Info,FoysLake_Info,Himchari_Info,Khaiyachora_Info,Chandranath_Info,Alutila_Info infoStyle;
class Abed_Info,Yunus_CTG_Info,FazlulHuq_Info,SuryaSen_Info,Pritilata_Info,ZiaurRahman_Info,Mahmudullah_Info,Shakib_Info,NasreenJahan_Info,SyedMujtaba_Info infoStyle;

class MymensinghCity_Info,Monda_Info,NakshiPitha_Info,Chitoi_Info,BhapaPitha_Info,Patishapta_Info,RutiPitha_Info,PuliPitha_Info,DudhPitha_Info,IlishBhapa_Info infoStyle;
class Brahmaputra_Info,ShashiLodge_Info,MymensinghMuseum_Info,BAU_Info,Birishiri_Info,Madhabkunda_Info,Hakaluki_Info,Tanguar_Info infoStyle;
class Zainul_MYM_Info,Humayun_MYM_Info,SyedNazrul_MYM_Info,AbuSayeed_Info,Shahabuddin_Info,Upendra_Info,Sukumar_Info,Leela_Info,Nirmalendu_Info,Helal_Info,Taslima_MYM_Info,Mahmudullah_MYM_Info infoStyle;

class RajshahiCity_Info,MangoDishes_Info,Chomchom_Info,Roshogolla_Info,Rasmalai_Info,Kheer_Info,Doi_Raj_Info,Pantua_Info,SilkMango_Info,Langcha_Info infoStyle;
class VarendraMuseum_Info,Puthia_Info,BaghaMosque_Info,MakhdumShrine_Info,Padma_Info,Paharpur_Info,Kantajew_Info,ChhotoSona_Info infoStyle;
class Zia_Raj_Info,AliBogra_Info,Pramatha_Info,Mushfiq_Info,Taijul_Info,Tunu_Info,Tipu_Info,BandeAli_Info,Amiya_Info,Andrew_Info,Sharmili_Info,Monjushree_Info infoStyle;
```
