# $firstname$ $lastname$

$for(address)$
$address$
$endfor$
$phone$
$email$

Date Prepared: $date$

## Education
$for(education)$
$education.year$	$education.degree$	$education.institute$
$endfor$
## Post-Graduate Training

$for(training)$
$training.start$--$training.end$	$training.institute$
		$training.program$
		$training.title$

$endfor$

## Licensure and Certification

### State Licensure
$for(license)$
$license.start$--$license.end$	$license.type$
$endfor$

## American Board of Psychiatry & Neurology Certification
$for(cert)$
$cert.date$		$cert.type$
$endfor$

## Honors and Awards

### National

$for(national_award)$
$national_award.date$	$national_award.name$
	$national_award.organization$

$endfor$

### University

$for(university_award)$
$university_award.date$	$university_award.name$
	$university_award.organization$
	$university_award.description$
$endfor$

## Professional Societies

### National Memberships
$for(national_membership)$
$national_membership.start$--$national_membership.end$ 		$national_membership.organization$
$endfor$

### Regional Memberships
$for(regional_membership)$
$regional_membership.start$--$regional_membership.end$ 		$regional_membership.organization$
$endfor$

### Leadership

$for(leadership)$
$leadership.start$--$leadership.end$ 		$leadership.position$
	$leadership.position$
	$leadership.organization$
$endfor$

## Teaching

### Northwestern University Feinberg School of Medicine

$for(teaching_northwestern)$
$teaching_northwestern.item$

$endfor$

### David Geffen School of Medicine at UCLA

$for(teaching_ucla)$
$teaching_ucla.item$
$endfor$

## Presentations

### Abstracts
(* denotes presenting author)
$for(abstract)$
$abstract.item$
$endfor$


### Advocacy and Public Service

### Grand Rounds and Lectures

## Publications

### Articles

### Book Chapters