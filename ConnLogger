while($true) {

    # Use the Test-Connection cmdlet to determine if the machine is responding
    $pinged = Test-Connection google.com -Count 1 -Quiet
    # Use an If statement to determine if the machine responded or not and output accordingly
    Start-Sleep -s 3
    If ($pinged) { Add-Content E:\test.txt "$(Get-Date -format 'u')- OK"  }
    Else { Add-Content E:\test.txt "$(Get-Date -format 'u') - BAD CONNECTION" }

}
