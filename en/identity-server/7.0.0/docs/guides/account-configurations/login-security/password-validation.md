# Password validation

Customize password validation rules to enhance the security of user accounts in {{product_name}}.

## Configuration instructions

To configure password validation rules, follow the steps below:

1. On the {{product_name}} Console, go to **Login & Registration** > **Login Security** > **Password Validation**.
2. Adjust the settings according to your security requirements.

    ![Password Validation Configuration]({{base_path}}/assets/img/guides/account-configurations/password-validation.png){: width="600" style="display: block; margin: 0;"}

    <table>
    <tr>
      <th>Parameter</th>
      <th>Description</th>
    </tr>
    <tr>
      <td><code>Password Expiration</code></td>
      <td>Defines the number of days after which a password must be changed.</td>
    </tr>
    <tr>
      <td><code>Password History Count</code></td>
      <td>Specifies the number of unique new passwords a user must use before an old password can be reused.</td>
    </tr>
    <tr>
      <td><code>Password Input Validation</code></td>
      <td>Sets requirements for password complexity, including length and character types.</td>
    </tr>
    </table>

3. Click **Update** to save the changes.

!!! note "Validation for whitespace in passwords"

    {{product_name}} automatically trims leading and trailing whitespace from passwords when creating, updating, or when entering passwords to login.