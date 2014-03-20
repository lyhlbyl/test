test, a second version of test 
-[] order function for data. Rule.mk not terminated - the following hack in 
       quantomatic/core/rewriting/rule.ML for Rule.mk required:

      in (Rule { lhs = lhs, rhs = rhs',
                lhs_aut = lhsauts,
                selfapps = [] (* GG: filterorbits lhsba [] *),
                order = [] (* GG: gen_ order lhs lhsauts
                                  V.NSet.empty V.NSet.empty *) },
          (vrn,ern))


- [ ] move socket stuff into isaplib [GG]
    -> still need to be tested and arra y stuff checked.

====
