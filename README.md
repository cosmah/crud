# crud
@Entity: This annotation indicates that the "Employee" class is an entity that will be mapped to a database table.

@Id: This annotation marks the field "id" as the primary key for the entity.

@GeneratedValue: This annotation specifies how the primary key should be generated. In this case, GenerationType.AUTO means that the persistence provider should choose an appropriate strategy for primary key generation, which is typically based on the database used.
