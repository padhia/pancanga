# Pancanga

http://www.cc.kyoto-su.ac.jp/~yanom/pancanga/

**Pancanga (version 3.14) --- Perl version --- March, 2014: by M. YANO and M. FUSHIMI**

- You can download the source script pancanga3.14 written in Perl language at the pancanga directory of Yano"s ftp server (pancanga3.13a is a slightly improved last version).
- (We have fixed a bag on the Julian date of the leap year between 1584 and 1752.)
- (We have fixed a bag on the *SaMkrAnti*)
- (We have deleted the position of the five planets so that we do not give misunderstandings)

This program offers a traditional Indian calendar based mainly on the *Suuryasiddhaanta*.

The *Suuryasiddhaanta* has a long history. The "original" version is quoted in Varaahamihirass Pancasiddhaantikaa in the mid-6th century. (See Neugebaur-Pingree's translation, Kopenhagen 1970.) The so-called "modern" *Suuryasiddhaanta* was most popular and influential all over India after about the 10th century. This text, together with the English translation by E. Burgess in 1860 (Journal of the American Oriental Society), has been a good starting point for the students of Indian astronomy. The astronomical constants in the two texts are slightly different. The default set is those of the so-called "modern *Suuryasiddhaanta*". You can choose a set of the old constants used in the *Pancaiddhaantikaa* as an option. For the time after AD 1000, the default set will fit better.

In traditional Indian calendar civil days in a half month are named by the current *tithi* at sunrise. We have given the fraction of *tithi* at sunrise in the verbose menu so that we can guess the possibility of different dates.

The default time of this program is set to the local time in Ujjain, the ancient center of astronomy, which played the role of Greenwich in the history of Indian calendar. The latitude of Ujjain is 23.2 degrees north and its longitude is 75.8 degrees east from Greenwich. In order to get the sunrise time of any intended locality, you need the latitude and longitude of the place. The difference in latitude can not be neglected, especially near the two solstices. The local latitude can be entered with the optional menu **L** in the first setting mode. The difference in longitude can slightly affect the time of conjunction and thus it can be one of the causes of one day difference of the date. From this version we added the option **O** , where the geographical longitude can be entered. Since, however, we do not know to what extent the longitudinal difference of the places (*dezaantara*) was taken into account in ancient calendar, we can proceed with the default longitude.

In this version we offer the following three menus.

## T: Modern date from Indian date

You can choose *Saka samvat* or *Vikrama samvat*. Sometimes you should take care whether a given year is expired (*atiita*) or current (*vartamaana*). Expired years are more common. Note that in the Indian Calendar Sewell-Dikshit used current years.

You should also take care whether the naming system is *amaanta* or *puurNimaanta* (see below).

The result of this menu is not always correct. Sometimes difference is one month because of the occurrence of *adhimaasa* (intercalary month) and, very rarely, *kSayamaasa* (omitted month). Thus the date can be shifted forward or backward by one month depending on the constant numbers which were used by calendar makers. You should confirm the result of this menu by the next menu L.

## L: Indian date from Modern date

To find the Indian date (in *amaanta*) from the given modern date in a tabular form. The result is considerably reliable: the occurrences of intercalary months almost always agree with those listed in Sewell-Dikshit"s Indian Calendar; only the difference of 1 day (or *tithi*) is to be admitted because of the different distribution of *kSayadina* (*omitted day*) and/or *adhidina* (*additional day*).

## V: Get more details
To get the further items of the *pancanga* (five elements) day by day. We have added the date in the traditional solar calendar. There are regional varieties concerning the beginning of a solar month. Our method is this: When a *saMkraanti* (sun"s entry in a new *nirayaNa* zodiacal sign) takes place before the midnight of a day, the first day of the solar month is on that day. When it takes place after the midnight, the first day of the solar month falls on the next day. For the sake of convenience we have shown the date and time of *saMkraanti*.

The *ayanaamsa* (difference of *nir-ayaNa* longitude and *sa-ayana* longitude due to the precession of equinoxes) is shown in this menu. According to the *Suuryasiddhaanta* the rate of precession is 54 seconds per year and the difference of the two longitudes was zero in A.D. 499. The modern value is about 50.29 seconds per year. This means that the *ayanaamsa* of this program is slightly different from that computed by the modern method.

We are not always consistent in Romanizing Sanskrit words. The Sanskrit names of Jovian year, yoga and *karaNa* are expressed in the Kyoto-Harvard transliteration system for network communication. Those who are not familiar with this system are advised to see the table of the [Kyoto-Harvard System](http://www.cc.kyoto-su.ac.jp/~yanom/pancanga/Kyoto-Harvard.html).

## NOTICE:
Remember that there are two different systems of naming the month, i.e. *amaanta* ("new moon ending") and *puurNimaanta* ("full moon ending"). In the bright half month (*zukla-pakSa*) nothing is different, but in the dark half month (*kRSNa-pakSa*), the *puurNimanta* month name is ahead of the *amaanta* month name by one.

In this program the beginning of the Indian year is set for *Caitra* month *zukla-pakSa* 1.

One can use this program for the B.C. years with negative numbers, for example, -57 = B.C. 58. But do not forget that the text on which this program is based belongs to the time after about A.D. 500.

From this version we have added the Julian date for the period from October 15, 1582 to September 13, 1752 in the menus list and verbose.

The copyright of this program belongs to the two authors. One can use this for the purpose of dating manuscripts, inscriptions etc. easily with a certain degrees of reliability. But we are not responsible for any inconvenience which might be caused by using this program. Suggestions for improvements are welcome.

If you have any questions, please contact:
- M.YANO (for Indian astronomy): yanom_at_cc.kyoto-su.ac.jp
- M.FUSHIMI (for programming): fushimi_at_fas.harvard.edu

This version was made possible by the Grant in Aid of the Ministry of Education, Science, Sports and Culture of the Japanese Government.

Last modified: Fri Jun 11 19:34:58 JST 2004
