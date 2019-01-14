# Medicatieviewer
Medication viewer for informatiestandaard Medicatieproces

	Copyright © Nictiz
	see https://www.nictiz.nl/

    This file is part of Medicatieviewer
	
	This program is free software; you can redistribute it and/or modify it under the terms of the
	GNU Lesser General Public License as published by the Free Software Foundation; either version
	3.0 of the License, or (at your option) any later version.
	
	This program is distributed in the hope that it will be useful, but WITHOUT ANY WARRANTY;
	without even the implied warranty of MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.
	See the GNU Lesser General Public License for more details.
	
	The full text of the license is available at http://www.gnu.org/copyleft/lesser.html
	
	==============================
	Medicatieviewer - gebruik
	==============================
	De Medicatieviewer transformeert een MP-9 XML volgens de standaard medicatieproces (https://www.nictiz.nl/standaardisatie/informatiestandaarden/informatiestandaard-medicatieproces/) voor medicatiegegevens of voor medicatieoverzicht in HTML om zo een voor mensen leesbaar overzicht te geven van de inhoud van de XML.
	Er is functionaliteit opgenomen om medicatiebouwstenen behorende bij dezelfde medicamenteuze behandeling samen te voegen en in samenhang te presenteren. 
	Daarbij wordt rekening gehouden met gebruiksperiode en afspraakdatum om volgordelijkheid en actualiteit te bepalen.
	Er is géén functionaliteit die de doseringsinstructies gestructureerd omzet, in plaats daarvan wordt alleen de tekstuele weergave uit het bericht getoond.
	
	Transformeer de MP-9 XML met de XSLT: cda_mp_health.xsl. Als output geeft dit een HTML.
		
