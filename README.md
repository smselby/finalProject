# finalProject
# list o' classes
CSC110 = {
    "name": "CSC-110 INTRO TO CMPTR PROGMING",
    "prereq": [],
    "all": True,
    "credits": 1
}
CSC142 = {
    "name": "CSC-142 COMPUTER PROG/EGR AND SC",
    "prereq": [],
    "all": True,
    "credits": 1
}
WEB105 = {
    "name": "WEB-105 WORKING ON A WEB PROJECT",
    "prereq": [],
    "Fall": True,
    "Winter": True,
    "credits": 1
}
WEB110 = {
    "name": "WEB-110 WEB AUTHORING I",
    "prereq": [],
    "all": True,
    "credits": 1
}
WEB120 = {
    "name": "WEB-120 WEB AUTHORING II",
    "prereq": [],
    "all": True,
    "credits": 1
}
WEB130 = {
    "name": "WEB-130 WEB AUTHORING III",
    "prereq": [],
    "Spring": True,
    "credits": 1
}
WEB150 = {
    "name": "WEB-150 INTRO TO JAVASCRIPT",
    "prereq": [],
    "Winter": True,
    "Spring": True,
    "credits": 1
}
ITC240 = {
    "name": "ITC-240 WEB APP PROGRAMMING 1",
    "prereq": [WEB110],
    "all": True,
    "credits": 1
}
ITC280 = {
    "name": "ITC-280",
    "prereq": [WEB110],
    "Summer": True,
    "credits": 1
}
WEB170 = {
    "name": "WEB-170 CONTENT MGMT SYSTEM",
    "prereq": [WEB120, ITC240, ITC280],
    "Fall": True,
    "Spring": True,
    "credits": 1
}
WEB200 = {
    "name": "WEB-200 THEORY OF WEB DESIGN",
    "prereq": [WEB110],
    "Winter": True,
    "Spring": True,
    "credits": 1
}
WEB202 = {
    "name": "WEB-202 USER INTERFACE DESIGN",
    "prereq": [WEB120, WEB200],
    "Spring": True,
    "credits": 1
}
WEB205 = {
    "name": "WEB-205 WEB CAREER STRATEGIES",
    "prereq": [WEB120],
    "Fall": True,
    "credits": 1
}
WEB210 = {
    "name": "WEB-210 ADVANCED WEB DESIGN",
    "prereq": [WEB120, WEB200],
    "Fall": True,
    "credits": 1
}
MATH092 = {
    "name": "MATH-092 DESCRIPTIVE STATISTICS",
    "prereq": [],
    "all": True,
    "credits": 1
}
MATH096 = {
    "name": "MATH-096 FOUNDATIONS ALGEBRA II",
    "prereq": [],
    "all": True,
    "credits": 1
}
MATH098 = {
    "name": "MATH-098 INTERMEDIATE ALGEBRA",
    "prereq": [],
    "all": True,
    "credits": 1
}
MATH116 = {
    "name": "MATH-116 Q-APPL MATH TO MGT LIFE",
    "prereq": [],
    "all": True,
    "credits": 1
}
MATH136 = {
    "name": "MATH-136 INFERENTIAL STATISTICS",
    "prereq": [MATH092, MATH098, MATH116],
    "all": True,
    "credits": 1
}
MATH146 = {
    "name": "MATH-146 Q-STATISTICS",
    "prereq": [MATH098, MATH116],
    "alt": MATH136,
    "all": True,
    "credits": 1
}
BUS140 = {
    "name": "BUS-140 CUSTOMER RELATIONS",
    "prereq": [],
    "all": True,
    "credits": 1
}
BUS240 = {
    "name": "BUS-240 iNTERNET LAW",
    "prereq": [],
    "all": True,
    "credits": 1
}
NET200 = {
    "name": "NET-200 ENTERPRISE APPLICATIONS",
    "prereq": [],
    "Fall": True,
    "credits": 1
}
MIC175 = {
    "name": "MIC-175 COMPUTER USER SUPPORT",
    "prereq": [],
    "alt": BUS140,
    "all": True,
    "credits": 1
}
ITC110 = {
    "name": "ITC-110 PROGRAM DESIGN & DEVELOP",
    "prereq": [],
    "alt": CSC110,
    "all": True,
    "credits": 1
}
ITC250 = {
    "name": "ITC-250 WEB APP PROGRAMMING 2",
    "prereq": [ITC240],
    "Winter": True,
    "Spring": True,
    "credits": 1
}
ITC115 = {
    "name": "ITC-115 OBJECT ORIENTED PROGRAM",
    "prereq": [ITC110],
    "alt": CSC142,
    "Winter": True,
    "credits": 1
}
ITC162 = {
    "name": "ITC-162 INTRO TO MOBIL DEVELOPMT",
    "prereq": [ITC115],
    "Spring": True,
    "credits": 1
}
ITC260 = {
    "name": "ITC-260 WEB APP PROGRAMMING 3",
    "prereq": [ITC250],
    "Spring": True,
    "credits": 1
}
CSC143 = {
    "name": "CSC-143 COMP PROGR II/ENGIN/SCI",
    "prereq": [],
    "alt": ITC162,
    "all": True,
    "credits": 1
}
ENGL101 = {
    "name": "ENGL-101 ENGLISH COMPOSITION I",
    "prereq": [],
    "all": True,
    "credits": 1
}
ENGL106 = {
    "name": "ENGL-106 TECHNICAL WRITING",
    "prereq": [],
    "Fall": True,
    "Winter": True,
    "credits": 1
}
HUM105 = {
    "name": "HUM-105 INTERCULTURAL COMMUNICATION",
    "prereq": [],
    "all": True,
    "credits": 1
}
ITC102 = {
    "name": "ITC-102 INFORMATION CMPT CONCPTS",
    "prereq": [],
    "all": True,
    "credits": 1
}

MIC101 = {
    "name": "MIC-101 INTRO TO MICRO COMP APPL",
    "prereq": [],
    "all": True,
    "credits": 1
}
ITC136 = {
    "name": "ITC-136 UNIX OPERATING SYSTEM",
    "prereq": [MIC101, ITC102],
    "all": True,
    "credits": 1
}
ITC140 = {
    "name": "ITC-140 INTRO TO COMPUTER HARDWARE",
    "prereq": [ITC102],
    "all": True,
    "credits": 1
}
NET120 = {
    "name": "NET-120 NETWORK COMMUNICATIONS I",
    "prereq": [MIC101],
    "all": True,
    "credits": 1
}
ITC151 = {
    "name": "ITC-151 INTRO NETWORK SECURITY",
    "prereq": [NET120],
    "Fall": True,
    "credits": 1
}
ITC172 = {
    "name": "ITC-172 .NET WEB PROGRAMMING",
    "prereq": [ITC110],
    "Winter": True,
    "Spring": True,
    "credits": 1
}
ITC197 = {
    "name": "ITC-197",
    "prereq": [],
    "credits": 1
}
ITC210 = {
    "name": "ITC-210 ADVANCED WEB DEVELOPMENT",
    "prereq": [ITC280],
    "Fall": True,
    "credits": 1
}
ITC220 = {
    "name": "ITC-220 DATABASE DEVELOPMENT",
    "prereq": [MIC101],
    "all": True,
    "credits": 1
}
ITC255 = {
    "name": "ITC-255 SYSTEMS ANALYSIS/DESIGN",
    "prereq": [ITC110],
    "Spring": True,
    "credits": 1
}
# CAN ONLY TAKE IN LAST QUARTER OF DEGREE
ITC285 = {
    "name": "ITC-285 CAPSTONE PROJECT CLASS",
    "prereq": [],
    "Spring": True,
    "credits": 1
}
# SPECIAL TOPIC
ITC298 = {
    "name": "ITC-298 SPECIAL TOPICS",
    "prereq": [],
    "Winter": True,
    "Spring": True,
    "credits": 1
}
# INDEPENDENT STUDY
ITC299 = {
    "name": "ITC-299 INDEPENDENT STUDY",
    "prereq": [],
    "all": True,
    "credits": 1
}
MATH119 = {
    "name": "MATH-119 MATH BEHIND INFO TECH",
    "prereq": [],
    "Spring": True,
    "credits": 1
}
NET122 = {
    "name": "NET-122 NETWORK OPERATING SYST 1",
    "prereq": [NET120],
    "Fall": True,
    "Winter": True,
    "credits": 1
}
NET134 = {
    "name": "NET-134 NETWORK COMMUNICATION-TCP/IP",
    "prereq": [NET122],
    "Fall": True,
    "Winter": True,
    "credits": 1
}
NET124 = {
    "name": "NET-124 NETWORK OPER SYSTEMS",
    "prereq": [NET134],
    "Spring": True,
    "credits": 1
}
NET126 = {
    "name": "NET-126 NET OPERATING SYSTEMS 3",
    "prereq": [NET122, NET134],
    "Winter": True,
    "Spring": True,
    "credits": 1
}
NET138 = {
    "name": "NET-138 UNIX FOR NETWORK ADMIN",
    "prereq": [ITC136],
    "Spring": True,
    "Summer": True,
    "credits": 1
}
NET142 = {
    "name": "NET-142 NETWORK MGT CISCO 1",
    "prereq": [ITC140],
    "Fall": True,
    "Winter": True,
    "credits": 1
}
NET144 = {
    "name": "NET-144 NETWORK MGT CISCO 2",
    "prereq": [NET142],
    "Winter": True,
    "Spring": True,
    "credits": 1
}
NET146 = {
    "name": "NET-146 NETWORK MGT CISCO 3",
    "prereq": [NET144],
    "Spring": True,
    "Summer": True,
    "credits": 1
}
# SPECIAL TOPIC
ITC298 = {
    "name": "ITC-298 NETWORK MGT, CISCO 4",
    "prereq": [],
    "Summer": True,
    "credits": 1
}

# list o' majors
# IMPORTANT: Do not put a class before its prerequisites
Network = [ENGL106, ITC102, ITC140, MATH092, MATH096, MATH098, MATH116, MATH119, MIC101, MIC175, ITC136, ITC151, NET120, NET122, NET124, NET126, NET134, NET138, NET142, NET144, NET146, NET200, ITC197, ENGL106, MATH146]
Programming = [ENGL106, ITC102, MATH092, MATH096, MATH098, MATH116, MATH119, MIC101, MIC175, ITC110, CSC143, ITC115, ITC172, ITC197, ITC220, ITC240, ITC250, ITC255, ITC280, ITC298, WEB110, ENGL101, HUM105, ITC285, MATH146]
WebDev = [ENGL106, ITC102, MATH092, MATH096, MATH098, MATH116, MATH119, MIC101, WEB110, ITC110, ITC115, ITC136, ITC172, ITC197, ITC210, ITC220, ITC240, ITC250, ITC280, ITC260, ITC298, WEB105, WEB110, WEB120, WEB130, WEB150, WEB170, WEB200, WEB202, WEB205, BUS240, ENGL101, HUM105, ITC285, MATH146]

def majorParse(m):  # takes input and turns it into variable
    return {
        'network': Network,
        'programming': Programming,
        'webdev': WebDev
    }.get(m, None)
def inParse(a):  # Takes user input and returns True/False/None
    i = ''.join(filter(str.isalpha, a))
    if i == "y":
        return True
    elif i == "n":
        return False
    else:
        print("I don't understand? Try y or n.")
        return None

def promptTaken(courseName):
    taken = None
    while taken is None:
        taken = inParse(input("Have you taken %s? (y/n) " % courseName))
    return taken
from realClasses import *
from coreLogic import *
from input import *

while True:
    major = majorParse(input("What is your major? (Network/Programming/WebDev) ").lower())  # set major.
    while major is None:  # for invalid input
        print("I didn't understand that")
        major = majorParse(input("What is your major? (Network/Programming/WebDev) ").lower())  # try again to set major.

    taken = []  # Classes that have already been taken and are, therefore, no longer required
    unTaken = []
    candidateClasses = []  # Classes you can take

    for c in major:  # Looks through list of required classes

        if c.get('classList', None) is not None:
            candidateClasses.extend(handleElect(c['classList'], taken, c['reqCredits']))
            continue

        extension = handleElect([c], taken, c['credits'])
        if extension is not None:
            candidateClasses.extend(extension)
    print("You can enrole in these classes:", candidateClasses)
