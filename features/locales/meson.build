# This is derived from the legacy Nmake src/cmd/std/features/locales feature
# test file.

feature_data.set10('_hdr_nl_types', cc.has_header('nl_types.h'))

if not cc.has_function('nl_langinfo', prefix: '#include <langinfo.h>', args: feature_test_args)
    error('No nl_langinfo() function could be found')
endif

# For now I'm omitting all the following tests since we've been building and
# testing ksh without them for a couple of months.
#
# TODO: Figure out if any of this is needed. Here is one such feature test
# translated from the original Nmake/iffe to Meson:
#
# if cc.has_member('struct lconv', 'credit_sign', prefix: '#include <locale.h>')
#     feature_data.set('_mem_credit_sign_lconv', 1)
# endif
#
#mem	lconv.credit_sign locale.h
#mem	lconv.currency_symbol locale.h
#mem	lconv.debit_sign locale.h
#mem	lconv.frac_digits locale.h
#mem	lconv.int_curr_symbol locale.h
#mem	lconv.int_frac_digits locale.h
#mem	lconv.left_parenthesis locale.h
#mem	lconv.mon_decimal_point locale.h
#mem	lconv.mon_grouping locale.h
#mem	lconv.mon_thousands_sep locale.h
#mem	lconv.n_cs_precedes locale.h
#mem	lconv.n_sep_by_space locale.h
#mem	lconv.n_sign_posn locale.h
#mem	lconv.negative_sign locale.h
#mem	lconv.p_cs_precedes locale.h
#mem	lconv.p_sep_by_space locale.h
#mem	lconv.p_sign_posn locale.h
#mem	lconv.positive_sign locale.h
#mem	lconv.right_parenthesis locale.h
#mem	lconv.decimal_point locale.h
#mem	lconv.grouping locale.h
#mem	lconv.thousands_sep locale.h
#
#num	_NL_ADDRESS_POSTAL_FMT langinfo.h
#num	_NL_ADDRESS_COUNTRY_NAME langinfo.h
#num	_NL_ADDRESS_COUNTRY_POST langinfo.h
#num	_NL_ADDRESS_COUNTRY_AB2 langinfo.h
#num	_NL_ADDRESS_COUNTRY_AB3 langinfo.h
#num	_NL_ADDRESS_COUNTRY_NUM langinfo.h
#num	_NL_ADDRESS_COUNTRY_CAR langinfo.h
#num	_NL_ADDRESS_COUNTRY_ISBN langinfo.h
#num	_NL_ADDRESS_LANG_NAME langinfo.h
#num	_NL_ADDRESS_LANG_AB langinfo.h
#num	_NL_ADDRESS_LANG_TERM langinfo.h
#num	_NL_ADDRESS_LANG_LIB langinfo.h
#num	_NL_IDENTIFICATION_TITLE langinfo.h
#num	_NL_IDENTIFICATION_SOURCE langinfo.h
#num	_NL_IDENTIFICATION_ADDRESS langinfo.h
#num	_NL_IDENTIFICATION_CONTACT langinfo.h
#num	_NL_IDENTIFICATION_EMAIL langinfo.h
#num	_NL_IDENTIFICATION_TEL langinfo.h
#num	_NL_IDENTIFICATION_FAX langinfo.h
#num	_NL_IDENTIFICATION_LANGUAGE langinfo.h
#num	_NL_IDENTIFICATION_TERRITORY langinfo.h
#num	_NL_IDENTIFICATION_REVISION langinfo.h
#num	_NL_IDENTIFICATION_DATE langinfo.h
#num	_NL_MEASUREMENT_MEASUREMENT langinfo.h
#num	_NL_NAME_NAME_FMT langinfo.h
#num	_NL_NAME_NAME_MISS langinfo.h
#num	_NL_NAME_NAME_MR langinfo.h
#num	_NL_NAME_NAME_MRS langinfo.h
#num	_NL_NAME_NAME_MS langinfo.h
#num	_NL_PAPER_HEIGHT langinfo.h
#num	_NL_PAPER_WIDTH langinfo.h
#num	_NL_TELEPHONE_TEL_INT_FMT langinfo.h
#num	_NL_TELEPHONE_TEL_DOM_FMT langinfo.h
#num	_NL_TELEPHONE_INT_SELECT langinfo.h
#num	_NL_TELEPHONE_INT_PREFIX langinfo.h
