package eu.deic.oop;

public class ProgMainFiling {

	private static double calculateTax(double income, FilingStatus filingStatus) {
		double tax = 0.0f;
		switch(filingStatus) {
		case SINGLE_FILERS:
			if(income >=0 && income <= 8350) {
				tax = income*0.1;
			} else if(income >=8351 && income <= 33950) {
				tax = income*0.15;
			} else if(income >=33951 && income <= 82250) {
				tax = income*0.25;
			} else if(income >=82251 && income <= 171550) {
				tax = income*0.28;
			} else if(income >=171551 && income <= 372950) {
				tax = income*0.33;
			}
			else if (income >= 372951) {
				tax = income*0.35;
			}
			break;
		case MARRIED_FILING_JOINTLY:
			if(income >=0 && income <= 16700) {
				tax = income*0.1;
			} else if(income >=16701 && income <= 67900) {
				tax = income*0.15;
			} else if(income >=67901 && income <= 137050) {
				tax = income*0.25;
			} else if(income >=137051 && income <= 208850) {
				tax = income*0.28;
			} else if(income >=208851 && income <= 372950) {
				tax = income*0.33;
			}
			else if (income >= 372951) {
				tax = income*0.35;
			}
			break;
		case MARRIED_FILING_SEPARATELY:
			if(income >=0 && income <= 8350) {
				tax = income*0.1;
			} else if(income >=8351 && income <= 33950) {
				tax = income*0.15;
			} else if(income >=33951 && income <= 68525) {
				tax = income*0.25;
			} else if(income >=68526 && income <= 104425) {
				tax = income*0.28;
			} else if(income >=104426 && income <= 186475) {
				tax = income*0.33;
			}
			else if (income >= 186476) {
				tax = income*0.35;
			}
			break;
		case HEAD_OF_HOUSEHOLD:
			if(income >=0 && income <= 11950) {
				tax = income*0.1;
			} else if(income >=11951 && income <= 45500) {
				tax = income*0.15;
			} else if(income >=45501 && income <= 117450) {
				tax = income*0.25;
			} else if(income >=117451 && income <= 190200) {
				tax = income*0.28;
			} else if(income >=190201 && income <= 372950) {
				tax = income*0.33;
			}
			else if (income >= 372951) {
				tax = income*0.35;
			}
			break;
		}
		return tax;
	}
	public static void main(String[] args) {
		FilingStatus fs = FilingStatus.HEAD_OF_HOUSEHOLD;
		double income = 357200;
		double tax = calculateTax(income, fs);
		System.out.println("At an income of " + income + " as a " + fs + " the tax value is " + tax);
	}

}
