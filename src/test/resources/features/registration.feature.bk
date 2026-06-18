Feature: Registration

  Scenario Outline: Succesfull regsitration
    Given Pepito wants to sign up in the application
    When Pepito sends the required information to sign up
      | <name> | <last name> | <age> | <email> | <country> |
    Then Pepito should have a new account created
    Examples:
      | name   | last name | age | email            | country  |
      | Julian | Mesa      | 26  | pepito@gmail.com | Colombia |
      | Pedro  | Perez     | 21  | pedro@gmail.com  | Colombia |

  Scenario: Missing required fields for regsitration
    Given Pepito wants to sign up in the application
    When Pepito does not send the required information
    Then Pepito should be told all fields are required

