# Quiz1_887342
US_states = 

	{"Alabama" => "AL",
	"Alaska" => "AK",
	"Arizona" => "AZ",
	"Arkansas" => "AR",
	"California" => "CA",
	"Colorado" => "CO",
	"Connecticut" => "CT",
	"Delaware" => "DE",
	"District of Columbia" => "DC",
	"Florida" => "FL",
	"Georgia" => "GA",
	"Hawaii" => "HI",
	"Idaho" => "ID",
	"Illinois" => "IL",
	"Indiana" => "IN",
	"Iowa" => "IA",
	"Kansas" => "KS",
	"Kentucky" => "KY",
	"Louisiana" => "LA",
	"Maine" => "ME",
	"Maryland" => "MD",
	"Massachusetts" => "MA",
	"Michigan" => "MI",
	"Minnesota" => "MN",
	"Mississippi" => "MS",
	"Missouri" => "MO",
	"Montana" => "MT",
	"Nebraska" => "NE",
	"Nevada" => "NV",
	"New Hampshire" => "NH",
	"New Jersey" => "NJ",
	"New Mexico" => "NM",
	"New York" => "NY",
	"North Carolina" => "NC",
	"North Dakota" => "ND",
	"Ohio" => "OH",
	"Oklahoma" => "OK",
	"Oregon" => "OR",
	"Pennsylvania" => "PA",
	"Rhode Island" => "RI",
	"South Carolina" => "SC",
	"South Dakota" => "SD",
	"Tennessee" => "TN",
	"Texas" => "TX",
	"Utah" => "UT",
	"Vermont" => "VT",
	"Virginia" => "VA",
	"Washington" => "WA",
	"West Virginia" => "WV",
	"Wisconsin" => "WI",
	"Wyoming" => "WY"}
print "==================================================================
"
US_states.each{|x,y| 
        if y[-1]=="N" || y[-1]=="T" 
            puts y
        end
    
}
print "==================================================================
"
puts US_states.sort.reverse
print "==================================================================
"
US_states.each{|x,y| 
if 
(x[0]=="A" || x[0]=="a" || 
x[0]=="E" || x[0]=="e" || 
x[0]=="I" || x[0]=="i" || 
x[0]=="O" || x[0]=="o" || 
x[0]=="U" || x[0]=="u") &&
(x[x.length-1]=="A" || x[x.length-1]=="a" || 
x[x.length-1]=="E" || x[x.length-1]=="e" || 
x[x.length-1]=="I" || x[x.length-1]=="i" || 
x[x.length-1]=="O" || x[x.length-1]=="o" || 
x[x.length-1]=="U" || x[x.length-1]=="u")
puts x
end
}
print "==================================================================
"

ข้อ2ยังทำไม่เสร็จนะครับเนื่องจากความสามารถผมยังไม่มากพอครับ
