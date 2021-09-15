# Config-Gnome-shell-extension-Clock-Override
How to install and set Ubuntu Gnome-shell extension Clock Override

1. Open Mozilla Firefox
2. Go to https://extensions.gnome.org/extension/1206/clock-override/
3. Add extension
4. Click on settings
5. Preferable clock format: %m.%d | %A %;cf %H:%M

If stuck and need to remove extension from Terminal before login:

1. Press Ctrl + Alt + F5
2. Go to /.local/share/gnome-shell/extensions
3. sudo rm -R "extension folder"


Date/Time Format Codes

This is a summary of standard date/time codes that may be used in format strings:
Valid format codes for custom subfolders

%a
	

The abbreviated weekday name according to the current locale.

%A
	

The full weekday name according to the current locale.

%b
	

The abbreviated month name according to the current locale.

%B
	

The full month name according to the current locale.

%c
	

The preferred date and time representation for the current locale.

%C
	

The century number (year/100) as a 2-digit integer.

%d
	

The day of the month as a decimal number (range 01 to 31).

%D
	

Equivalent to %m/%d/%y. (Yecch -- for Americans only. Americans should note that in other countries %d/%m/%y is rather common. This means that in international context this format is ambiguous and should not be used.)

%e
	

Like %d, the day of the month as a decimal number, but a leading zero is replaced by a space.

%E
	

Modifier: use alternative format, see below.

%F
	

Equivalent to %Y-%m-%d (the ISO 8601 date format). (C99)

%G
	

The ISO 8601 year with century as a decimal number. The 4-digit year corresponding to the ISO week number (see %V). This has the same format and value as %y, except that if the ISO week number belongs to the previous or next year, that year is used instead.

%g
	

Like %G, but without century, i.e., with a 2-digit year (00-99).

%h
	

Equivalent to %b.

%H
	

The hour as a decimal number using a 24-hour clock (range 00 to 23).

%I
	

The hour as a decimal number using a 12-hour clock (range 01 to 12).

%j
	

The day of the year as a decimal number (range 001 to 366).

%k
	

The hour (24-hour clock) as a decimal number (range 0 to 23); single digits are preceded by a blank. (See also %H.)

%l
	

The hour (12-hour clock) as a decimal number (range 1 to 12); single digits are preceded by a blank. (See also %I.)

%m
	

The month as a decimal number (range 01 to 12).

%M
	

The minute as a decimal number (range 00 to 59).

%O
	

Modifier: use alternative format, see below.

%p
	

Either 'AM' or 'PM' according to the given time value, or the corresponding strings for the current locale. Noon is treated as 'pm' and midnight as 'am'.

%P
	

Like %p but in lowercase: 'am' or 'pm' or a corresponding string for the current locale.

%r
	

The time in a.m. or p.m. notation. In the POSIX locale this is equivalent to '%I:%M:%S %p'.

%R
	

The time in 24-hour notation (%H:%M). For a version including the seconds, see %T below.

%s
	

The number of seconds since the Epoch, i.e., since 1970-01-01 00:00:00 UTC.

%S
	

The second as a decimal number (range 00 to 60). (The range is up to 60 to allow for occasional leap seconds.)

%T
	

The time in 24-hour notation (%H:%M:%S).

%u
	

The day of the week as a decimal number, range 1 to 7, Monday being 1. See also %w.

%U
	

The week number of the current year as a decimal number, range 00 to 53, starting with the first Sunday as the first day of week 01. See also %V and %W.

%V
	

The ISO 8601:1988 week number of the current year as a decimal number, range 01 to 53, where week 1 is the first week that has at least 4 days in the current year, and with Monday as the first day of the week. See also %U and %W.

%w
	

The day of the week as a decimal, range 0 to 6, Sunday being 0. See also %u.

%W
	

The week number of the current year as a decimal number, range 00 to 53, starting with the first Monday as the first day of week 01.

%x
	

The preferred date representation for the current locale without the time.

%X
	

The preferred time representation for the current locale without the date.

%y
	

The year as a decimal number without a century (range 00 to 99).

%Y
	

The year as a decimal number including the century.

%z
	

The time-zone as hour offset from GMT. Required to emit RFC 822-conformant dates (using "%a, %d %b %Y %H:%M:%S %z").

%Z
	

The time zone or name or abbreviation.
