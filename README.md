# Anti DMCA bot


## .env file example
```bash
# Default: 3111
SERVER_PORT=

# Default: 0.0.0.0
SERVER_HOST=

# Defauld: sc-noreply@google.com
LEGAL_EMAIL_ADDRESS=

#! Requared property
# Create oauth app to google api https://console.cloud.google.com/apis/library/gmail.googleapis.com
# Set secret properties
CLIENT_ID=""
CLIENT_SECRET=""

# Example: https://example.com
HOST_URL=""

# Example: mongodb+srv://<login>:<password>@<host>|:<port>/<db>
DATABASE_URL=""

# Example: my-hit.online
DOMAIN=""

# Your country
# Values: australia | austria | azerbaijan | aland_islands | albania | algeria | american_samoa | anguilla | angola | andorra | antarctica | antigua_and_barbuda | argentina | armenia | aruba | afghanistan | bahamas | bangladesh | barbados | bahrain | belarus | belize | belgium | benin | bermuda | bulgaria | bolivia | bosnia_and_herzegovina | botswana | brazil | british_indian_ocean_territory | british_virgin_islands | brunei | burkina_faso | burundi | bhutan | vanuatu | vatican_city | united_kingdom | hungary | venezuela | us_virgin_islands | us_outlying_islands | timor_leste | vietnam | gabon | haiti | guyana | gambia | ghana | guadeloupe | guatemala | guinea | guinea_bissau | germany | guernsey | gibraltar | honduras | hong_kong | grenada | greenland | greece | georgia | guam | denmark | congo_kinshasa | jersey | djibouti | dominica | dominican_republic | egypt | zambia | western_sahara | zimbabwe | israel | india | indonesia | jordan | iraq | iran | ireland | iceland | spain | italy | yemen | cape_verde | kazakhstan | cayman_islands | cambodia | cameroon | canada | caribbean_netherlands | qatar | kenya | cyprus | kyrgyzstan | kiribati | china | cocos_keeling_islands | colombia | comoros | congo_brazzaville | kosovo | costa_rica | cote_d_ivoire | cuba | kuwait | curacao | laos | latvia | lesotho | liberia | lebanon | libya | lithuania | liechtenstein | luxembourg | mauritius | mauritania | madagascar | mayotte | macao | malawi | malaysia | mali | maldives | malta | morocco | martinique | marshall_islands | mexico | micronesia | mozambique | moldova | monaco | mongolia | montserrat | myanmar_burma | namibia | nauru | nepal | niger | nigeria | netherlands | nicaragua | niue | new_zealand | new_caledonia | norway | united_arab_emirates | oman | bouvet_island | ascension_island | isle_of_man | norfolk_island | christmas_island | st_helena | heard_and_mcdonald_islands | cook_islands | turks_and_caicos_islands | pakistan | palau | palestine | panama | papua_new_guinea | paraguay | peru | pitcairn_islands | poland | portugal | puerto_rico | south_korea | reunion | russia | rwanda | romania | united_states | el_salvador | samoa | san_marino | sao_tome_and_principe | saudi_arabia | north_macedonia | northern_mariana_islands | seychelles | saint_barthelemy | st_barthelemy | st_martin | saint_martin_french_part | st_pierre_and_miquelon | saint_pierre_and_miquelon | senegal | st_vincent_and_grenadines | st_kitts_and_nevis | st_lucia | serbia | singapore | sint_maarten | syrian_arab_republic | slovakia | slovenia | solomon_islands | somalia | sudan | suriname | sierra_leone | tajikistan | thailand | taiwan | tanzania | togo | tokelau | tonga | trinidad_and_tobago | tristan_da_cunha | tuvalu | tunisia | turkmenistan | turkey | uganda | uzbekistan | ukraine | wallis_and_futuna | uruguay | faroe_islands | fiji | philippines | finland | falkland_islands_islas_malvinas | france | french_guiana | french_polynesia | french_southern_territories | croatia | central_african_republic | chad | montenegro | czechia | chile | switzerland | sweden | svalbard_and_jan_mayen | sri_lanka | ecuador | equatorial_guinea | eritrea | eswatini | estonia | ethiopia | south_georgia_and_south_sandwich_islands | south_africa | south_sudan | jamaica | 
# Example: russia
COUNTRY_NAME=""
# Example: Jone Doe
FULL_NAME=""
# Example: Administrator
YOUR_TITLE=""

# Optionsl
# Example: DATA MOVE
COMPANY_NAME=""
# Example: example@gmail.com
CONTACT_EMAIL=""
# Example: 11111 Russia, Moscow, Arbat 99
ADDRESS=""
# Exmple: +7999999999
PHONE=""

# Why are you requesting reinstatement?
# Select one of the options below. *
# 1: I am the owner of the content
# 2: I am not the owner, but I am authorized to use the content
# 3: The complainant does not have the right to submit this request
# 4: The way I used the content is fair use (What is fair use?)
# 5: I never used the content
# 6: Other
# Example: 4
REASON=""
# Example: There are no online movies on the site, only information about them.
DMCA_CLARIFICATIONS=""
# Example: Jone Doe
SIGNATURE=""
```