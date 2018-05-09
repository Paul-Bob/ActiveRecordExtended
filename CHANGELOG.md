# 0.3.0 - May 9th 2018

- Fixed ActiveRecord QueryMethod constant load error.

# 0.2.1 - May 6th 2018

Changed how where clause is required. This is to hopefully future proof the next minior update to ActiveRecord.

# 0.2.0 - May 6th 2018

Added ActiveRecord Where Chain Functionality
- .where.any_of
- .where.none_of

Major thanks to [Olivier El Mekki author of ActiveRecord AnyOf](https://github.com/oelmekki/activerecord_any_of)

# 0.1.1 - May 2nd 2018

Added ActiveRecord Where Chain Functionality:
- .where.overlap
- .where.contained_within
- .where.contained_within_or_equals
- .where.contains_or_equals
- .where.any/1
- .where.all/1

Major thanks to [Dan McClain author of Postgres Ext](https://github.com/dockyard/postgres_ext)

Added ActiveRecord Base Extentions
- .either_order/2
- .either_join/2
