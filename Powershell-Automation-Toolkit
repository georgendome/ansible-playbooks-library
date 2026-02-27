Import-Module ActiveDirectory

$UserFirst = "John"
$UserLast = "Doe"
$UserName = "$UserFirst.$UserLast"

New-ADUser `
    -Name "$UserFirst $UserLast" `
    -GivenName $UserFirst `
    -Surname $UserLast `
    -SamAccountName $UserName `
    -UserPrincipalName "$UserName@domain.com" `
    -Path "OU=Users,DC=domain,DC=com" `
    -Enabled $true `
    -AccountPassword (ConvertTo-SecureString "TempPass123!" -AsPlainText -Force)
