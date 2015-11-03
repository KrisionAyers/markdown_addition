# Addition Game
Playing a Addition game!

## Code
``` java
import java.util.Scanner;
public class Addition_Game {
	public static void main(String[] args) {
		System.out.println("Hello Class!");
		
		// Outline for addition problem.
		int score = 0;
		int hardness = 10;
		
		// Round 1
		//	Generate 2 random numbers
		int number1 = (int)(Math.random() * hardness);
		int number2 = (int)(Math.random() * hardness);
		int correctAnswer = number1 + number2;
		
		//  Ask the user to add these two numbers together
		System.out.println("What integer is " + number1 + " + " + number2 + "?");
		System.out.println("Please enter integers only.");
		//  Read in their response
		Scanner input = new Scanner(System.in);
		int studentAnswer = input.nextInt();
		//  Check if the answer was correct
		if(studentAnswer == correctAnswer){
			//		IF correct
			//			Tell them it was correct
			System.out.println("Your answer was correct.");
			//			Give them points
			score += hardness;
			System.out.println("Your score is now: " + score);
			//			Make the next question harder
			hardness *= 10;
			System.out.println("The next hardness will be: " + hardness);
		}else{
			//		IF not correct
			//			Tell them it was wrong
			System.out.println("Your answer was not correct.");
			// 			Tell them the correct answer
			System.out.println("The correct answer was: " + correctAnswer);
			//			Do not give them points
			score += 0;
			//			Make the next question easier
			if (hardness > 10){
				hardness /= 10;
				System.out.println("Your hardness is now: " + hardness);
			}else{
				System.out.println("Your hardness is at the lowest level");
				System.out.println("Your hardness is now: " + hardness);
			}
			
			
		}

		System.out.println("End of round 1.");
		
		// Round 2
		//	Generate 2 random numbers
		number1 = (int)(Math.random() * hardness);
		number2 = (int)(Math.random() * hardness);
		correctAnswer = number1 + number2;
		
		//  Ask the user to add these two numbers together
		System.out.println("What integer is " + number1 + " + " + number2 + "?");
		System.out.println("Please enter integers only.");
		//  Read in their response
		//Scanner input = new Scanner(System.in);
		studentAnswer = input.nextInt();
		//  Check if the answer was correct
		if(studentAnswer == correctAnswer){
			//		IF correct
			//			Tell them it was correct
			System.out.println("Your answer was correct.");
			//			Give them points
			score += hardness;
			System.out.println("Your score is now: " + score);
			//			Make the next question harder
			hardness *= 10;
			System.out.println("The next hardness will be: " + hardness);
		}else{
			//		IF not correct
			//			Tell them it was wrong
			System.out.println("Your answer was not correct.");
			// 			Tell them the correct answer
			System.out.println("The correct answer was: " + correctAnswer);
			//			Do not give them points
			score += 0;
			//			Make the next question easier
			if (hardness > 10){
				hardness /= 10;
				System.out.println("Your hardness is now: " + hardness);
			}else{
				System.out.println("Your hardness is at the lowest level");
				System.out.println("Your hardness is now: " + hardness);
			}
			
			
		}

		System.out.println("End of round 2.");
		
		// Round 3
//		Generate 2 random numbers
		number1 = (int)(Math.random() * hardness);
		number2 = (int)(Math.random() * hardness);
		correctAnswer = number1 + number2;
		
		//  Ask the user to add these two numbers together
		System.out.println("What integer is " + number1 + " + " + number2 + "?");
		System.out.println("Please enter integers only.");
		//  Read in their response
		//Scanner input = new Scanner(System.in);
		studentAnswer = input.nextInt();
		//  Check if the answer was correct
		if(studentAnswer == correctAnswer){
			//		IF correct
			//			Tell them it was correct
			System.out.println("Your answer was correct.");
			//			Give them points
			score += hardness;
			System.out.println("Your score is now: " + score);
			//			Make the next question harder
			hardness *= 10;
			System.out.println("The next hardness will be: " + hardness);
		}else{
			//		IF not correct
			//			Tell them it was wrong
			System.out.println("Your answer was not correct.");
			// 			Tell them the correct answer
			System.out.println("The correct answer was: " + correctAnswer);
			//			Do not give them points
			score += 0;
			//			Make the next question easier
			if (hardness > 10){
				hardness /= 10;
				System.out.println("Your hardness is now: " + hardness);
			}else{
				System.out.println("Your hardness is at the lowest level");
				System.out.println("Your hardness is now: " + hardness);
			}
			
			
		}

		System.out.println("End of round 3.");
		// Round 4
//		Generate 2 random numbers
		number1 = (int)(Math.random() * hardness);
		number2 = (int)(Math.random() * hardness);
		correctAnswer = number1 + number2;
		
		//  Ask the user to add these two numbers together
		System.out.println("What integer is " + number1 + " + " + number2 + "?");
		System.out.println("Please enter integers only.");
		//  Read in their response
		//Scanner input = new Scanner(System.in);
		studentAnswer = input.nextInt();
		//  Check if the answer was correct
		if(studentAnswer == correctAnswer){
			//		IF correct
			//			Tell them it was correct
			System.out.println("Your answer was correct.");
			//			Give them points
			score += hardness;
			System.out.println("Your score is now: " + score);
			//			Make the next question harder
			hardness *= 10;
			System.out.println("The next hardness will be: " + hardness);
		}else{
			//		IF not correct
			//			Tell them it was wrong
			System.out.println("Your answer was not correct.");
			// 			Tell them the correct answer
			System.out.println("The correct answer was: " + correctAnswer);
			//			Do not give them points
			score += 0;
			//			Make the next question easier
			if (hardness > 10){
				hardness /= 10;
				System.out.println("Your hardness is now: " + hardness);
			}else{
				System.out.println("Your hardness is at the lowest level");
				System.out.println("Your hardness is now: " + hardness);
			}
			
			
		}

		System.out.println("End of round 4.");
		System.out.println("Your final score is: " + score);



	}
}
```

## Console Output
```
Your answer was correct.
Your score is now: 10
The next hardness will be: 100
End of round 1.
What integer is 86 + 77?
Please enter integers only.
163
Your answer was correct.
Your score is now: 110
The next hardness will be: 1000
End of round 2.
What integer is 211 + 308?
Please enter integers only.
519
Your answer was correct.
Your score is now: 1110
The next hardness will be: 10000
End of round 3.
What integer is 7177 + 8042?
Please enter integers only.
15219
Your answer was correct.
Your score is now: 11110
The next hardness will be: 100000
End of round 4.
Your final score is: 11110
```

## Command Prompt Output
``` java
.ui.themes_1.1.0.v20150511-0913/images/winXPBlue.png
 create mode 100644 eclipse-java-mars-R-win32-x86_64/eclipse/plugins/org.eclipse
.ui.themes_1.1.0.v20150511-0913/images/winXPHandle.png
 create mode 100644 eclipse-java-mars-R-win32-x86_64/eclipse/plugins/org.eclipse
.ui.themes_1.1.0.v20150511-0913/images/winXPOlive.png
 create mode 100644 eclipse-java-mars-R-win32-x86_64/eclipse/plugins/org.eclipse
.ui.themes_1.1.0.v20150511-0913/images/winXPTSFrame.png
 create mode 100644 eclipse-java-mars-R-win32-x86_64/eclipse/plugins/org.eclipse
.ui.themes_1.1.0.v20150511-0913/plugin.properties
 create mode 100644 eclipse-java-mars-R-win32-x86_64/eclipse/plugins/org.eclipse
.ui.themes_1.1.0.v20150511-0913/plugin.xml
 create mode 100644 eclipse-java-mars-R-win32-x86_64/eclipse/plugins/org.eclipse
.ui.views.log_1.0.600.v20150513-1840.jar
 create mode 100644 eclipse-java-mars-R-win32-x86_64/eclipse/plugins/org.eclipse
.ui.views.properties.tabbed_3.6.100.v20150423-0822.jar
 create mode 100644 eclipse-java-mars-R-win32-x86_64/eclipse/plugins/org.eclipse
.ui.views_3.8.0.v20150422-0725.jar
 create mode 100644 eclipse-java-mars-R-win32-x86_64/eclipse/plugins/org.eclipse
.ui.win32_3.2.500.v20150423-0822.jar
 create mode 100644 eclipse-java-mars-R-win32-x86_64/eclipse/plugins/org.eclipse
.ui.workbench.texteditor_3.9.100.v20141023-1946.jar
 create mode 100644 eclipse-java-mars-R-win32-x86_64/eclipse/plugins/org.eclipse
.ui.workbench_3.107.0.v20150510-1732.jar
 create mode 100644 eclipse-java-mars-R-win32-x86_64/eclipse/plugins/org.eclipse
.ui_3.107.0.v20150507-1945.jar
 create mode 100644 eclipse-java-mars-R-win32-x86_64/eclipse/plugins/org.eclipse
.update.configurator_3.3.300.v20140518-1928.jar
 create mode 100644 eclipse-java-mars-R-win32-x86_64/eclipse/plugins/org.eclipse
.wb.core.databinding_1.8.0.r45x201506110821.jar
 create mode 100644 eclipse-java-mars-R-win32-x86_64/eclipse/plugins/org.eclipse
.wb.core.java_1.8.0.r45x201506110821.jar
 create mode 100644 eclipse-java-mars-R-win32-x86_64/eclipse/plugins/org.eclipse
.wb.core.lib_1.8.0.r45x201506110820/META-INF/ECLIPSE_.RSA
 create mode 100644 eclipse-java-mars-R-win32-x86_64/eclipse/plugins/org.eclipse
.wb.core.lib_1.8.0.r45x201506110820/META-INF/ECLIPSE_.SF
 create mode 100644 eclipse-java-mars-R-win32-x86_64/eclipse/plugins/org.eclipse
.wb.core.lib_1.8.0.r45x201506110820/META-INF/MANIFEST.MF
 create mode 100644 eclipse-java-mars-R-win32-x86_64/eclipse/plugins/org.eclipse
.wb.core.lib_1.8.0.r45x201506110820/META-INF/eclipse.inf
 create mode 100644 eclipse-java-mars-R-win32-x86_64/eclipse/plugins/org.eclipse
.wb.core.lib_1.8.0.r45x201506110820/about.html
 create mode 100644 eclipse-java-mars-R-win32-x86_64/eclipse/plugins/org.eclipse
.wb.core.lib_1.8.0.r45x201506110820/lib/MVEL-fork.jar
 create mode 100644 eclipse-java-mars-R-win32-x86_64/eclipse/plugins/org.eclipse
.wb.core.lib_1.8.0.r45x201506110820/lib/asm-all-3.3.1.jar
 create mode 100644 eclipse-java-mars-R-win32-x86_64/eclipse/plugins/org.eclipse
.wb.core.lib_1.8.0.r45x201506110820/lib/commons-beanutils-1.8.0.jar
 create mode 100644 eclipse-java-mars-R-win32-x86_64/eclipse/plugins/org.eclipse
.wb.core.lib_1.8.0.r45x201506110820/lib/commons-collections-3.2.1.jar
 create mode 100644 eclipse-java-mars-R-win32-x86_64/eclipse/plugins/org.eclipse
.wb.core.lib_1.8.0.r45x201506110820/lib/commons-digester-2.0.jar
 create mode 100644 eclipse-java-mars-R-win32-x86_64/eclipse/plugins/org.eclipse
.wb.core.lib_1.8.0.r45x201506110820/lib/commons-io-2.0.1.jar
 create mode 100644 eclipse-java-mars-R-win32-x86_64/eclipse/plugins/org.eclipse
.wb.core.lib_1.8.0.r45x201506110820/lib/commons-lang-2.5.jar
 create mode 100644 eclipse-java-mars-R-win32-x86_64/eclipse/plugins/org.eclipse
.wb.core.lib_1.8.0.r45x201506110820/lib/commons-logging-1.1.1.jar
 create mode 100644 eclipse-java-mars-R-win32-x86_64/eclipse/plugins/org.eclipse
.wb.core.lib_1.8.0.r45x201506110820/lib/commons-primitives-1.0.jar
 create mode 100644 eclipse-java-mars-R-win32-x86_64/eclipse/plugins/org.eclipse
.wb.core.lib_1.8.0.r45x201506110820/lib/guava-13.0.1.jar
 create mode 100644 eclipse-java-mars-R-win32-x86_64/eclipse/plugins/org.eclipse
.wb.core.lib_1.8.0.r45x201506110820/lib/nebula-cdatetime.jar
 create mode 100644 eclipse-java-mars-R-win32-x86_64/eclipse/plugins/org.eclipse
.wb.core.lib_1.8.0.r45x201506110820/lib/nebula-cwt.jar
 create mode 100644 eclipse-java-mars-R-win32-x86_64/eclipse/plugins/org.eclipse
.wb.core.lib_1.8.0.r45x201506110820/plugin.properties
 create mode 100644 eclipse-java-mars-R-win32-x86_64/eclipse/plugins/org.eclipse
.wb.core.lib_1.8.0.r45x201506110820/target.properties
 create mode 100644 eclipse-java-mars-R-win32-x86_64/eclipse/plugins/org.eclipse
.wb.core.ui_1.8.0.r45x201506110822.jar
 create mode 100644 eclipse-java-mars-R-win32-x86_64/eclipse/plugins/org.eclipse
.wb.core_1.8.0.r45x201506110820.jar
 create mode 100644 eclipse-java-mars-R-win32-x86_64/eclipse/plugins/org.eclipse
.wb.layout.group_1.8.0.r45x201506110824.jar
 create mode 100644 eclipse-java-mars-R-win32-x86_64/eclipse/plugins/org.eclipse
.wb.os.win32_1.8.0.r45x201506110820.jar
 create mode 100644 eclipse-java-mars-R-win32-x86_64/eclipse/plugins/org.eclipse
.wb.os_1.8.0.r45x201506110820.jar
 create mode 100644 eclipse-java-mars-R-win32-x86_64/eclipse/plugins/org.eclipse
.wb.runtime.lib_1.8.0.r45x201506110820/META-INF/ECLIPSE_.RSA
 create mode 100644 eclipse-java-mars-R-win32-x86_64/eclipse/plugins/org.eclipse
.wb.runtime.lib_1.8.0.r45x201506110820/META-INF/ECLIPSE_.SF
 create mode 100644 eclipse-java-mars-R-win32-x86_64/eclipse/plugins/org.eclipse
.wb.runtime.lib_1.8.0.r45x201506110820/META-INF/MANIFEST.MF
 create mode 100644 eclipse-java-mars-R-win32-x86_64/eclipse/plugins/org.eclipse
.wb.runtime.lib_1.8.0.r45x201506110820/META-INF/eclipse.inf
 create mode 100644 eclipse-java-mars-R-win32-x86_64/eclipse/plugins/org.eclipse
.wb.runtime.lib_1.8.0.r45x201506110820/about.html
 create mode 100644 eclipse-java-mars-R-win32-x86_64/eclipse/plugins/org.eclipse
.wb.runtime.lib_1.8.0.r45x201506110820/lib/cglib-nodep-2.2.jar
 create mode 100644 eclipse-java-mars-R-win32-x86_64/eclipse/plugins/org.eclipse
.wb.runtime.lib_1.8.0.r45x201506110820/lib/cglib-nodep-2.2.zip
 create mode 100644 eclipse-java-mars-R-win32-x86_64/eclipse/plugins/org.eclipse
.wb.runtime.lib_1.8.0.r45x201506110820/plugin.properties
 create mode 100644 eclipse-java-mars-R-win32-x86_64/eclipse/plugins/org.eclipse
.wb.runtime.lib_1.8.0.r45x201506110820/target.properties
 create mode 100644 eclipse-java-mars-R-win32-x86_64/eclipse/plugins/org.eclipse
.wb.runtime_1.8.0.r45x201506110820.jar
 create mode 100644 eclipse-java-mars-R-win32-x86_64/eclipse/plugins/org.eclipse
.wb.swing.FormLayout.lib_1.8.0.r45x201506110826/META-INF/ECLIPSE_.RSA
 create mode 100644 eclipse-java-mars-R-win32-x86_64/eclipse/plugins/org.eclipse
.wb.swing.FormLayout.lib_1.8.0.r45x201506110826/META-INF/ECLIPSE_.SF
 create mode 100644 eclipse-java-mars-R-win32-x86_64/eclipse/plugins/org.eclipse
.wb.swing.FormLayout.lib_1.8.0.r45x201506110826/META-INF/MANIFEST.MF
 create mode 100644 eclipse-java-mars-R-win32-x86_64/eclipse/plugins/org.eclipse
.wb.swing.FormLayout.lib_1.8.0.r45x201506110826/META-INF/eclipse.inf
 create mode 100644 eclipse-java-mars-R-win32-x86_64/eclipse/plugins/org.eclipse
.wb.swing.FormLayout.lib_1.8.0.r45x201506110826/about.html
 create mode 100644 eclipse-java-mars-R-win32-x86_64/eclipse/plugins/org.eclipse
.wb.swing.FormLayout.lib_1.8.0.r45x201506110826/jgoodies-common-1.8.0-sources.ja
r
 create mode 100644 eclipse-java-mars-R-win32-x86_64/eclipse/plugins/org.eclipse
.wb.swing.FormLayout.lib_1.8.0.r45x201506110826/jgoodies-common-1.8.0.jar
 create mode 100644 eclipse-java-mars-R-win32-x86_64/eclipse/plugins/org.eclipse
.wb.swing.FormLayout.lib_1.8.0.r45x201506110826/jgoodies-forms-1.8.0-sources.jar

 create mode 100644 eclipse-java-mars-R-win32-x86_64/eclipse/plugins/org.eclipse
.wb.swing.FormLayout.lib_1.8.0.r45x201506110826/jgoodies-forms-1.8.0.jar
 create mode 100644 eclipse-java-mars-R-win32-x86_64/eclipse/plugins/org.eclipse
.wb.swing.FormLayout.lib_1.8.0.r45x201506110826/plugin.properties
 create mode 100644 eclipse-java-mars-R-win32-x86_64/eclipse/plugins/org.eclipse
.wb.swing.FormLayout.lib_1.8.0.r45x201506110826/target.properties
 create mode 100644 eclipse-java-mars-R-win32-x86_64/eclipse/plugins/org.eclipse
.wb.swing.FormLayout_1.8.0.r45x201506110826.jar
 create mode 100644 eclipse-java-mars-R-win32-x86_64/eclipse/plugins/org.eclipse
.wb.swing.MigLayout.lib_1.8.0.r45x201506110826.jar
 create mode 100644 eclipse-java-mars-R-win32-x86_64/eclipse/plugins/org.eclipse
.wb.swing.MigLayout_1.8.0.r45x201506110826.jar
 create mode 100644 eclipse-java-mars-R-win32-x86_64/eclipse/plugins/org.eclipse
.wb.swing.databinding_1.8.0.r45x201506110826.jar
 create mode 100644 eclipse-java-mars-R-win32-x86_64/eclipse/plugins/org.eclipse
.wb.swing.java6_1.8.0.r45x201506110826.jar
 create mode 100644 eclipse-java-mars-R-win32-x86_64/eclipse/plugins/org.eclipse
.wb.swing.jsr296_1.8.0.r45x201506110826.jar
 create mode 100644 eclipse-java-mars-R-win32-x86_64/eclipse/plugins/org.eclipse
.wb.swing_1.8.0.r45x201506110826.jar
 create mode 100644 eclipse-java-mars-R-win32-x86_64/eclipse/plugins/org.eclipse
.wst.common.core_1.2.0.v200908251833.jar
 create mode 100644 eclipse-java-mars-R-win32-x86_64/eclipse/plugins/org.eclipse
.wst.common.emf_1.2.400.v201505132009.jar
 create mode 100644 eclipse-java-mars-R-win32-x86_64/eclipse/plugins/org.eclipse
.wst.common.emfworkbench.integration_1.2.101.v201107081800.jar
 create mode 100644 eclipse-java-mars-R-win32-x86_64/eclipse/plugins/org.eclipse
.wst.common.environment_1.0.400.v200912181831.jar
 create mode 100644 eclipse-java-mars-R-win32-x86_64/eclipse/plugins/org.eclipse
.wst.common.frameworks.ui_1.2.400.v201504292002.jar
 create mode 100644 eclipse-java-mars-R-win32-x86_64/eclipse/plugins/org.eclipse
.wst.common.frameworks_1.2.200.v201304241450.jar
 create mode 100644 eclipse-java-mars-R-win32-x86_64/eclipse/plugins/org.eclipse
.wst.common.infopop_1.0.300.v201309101952.jar
 create mode 100644 eclipse-java-mars-R-win32-x86_64/eclipse/plugins/org.eclipse
.wst.common.modulecore.ui_1.0.300.v201505072128.jar
 create mode 100644 eclipse-java-mars-R-win32-x86_64/eclipse/plugins/org.eclipse
.wst.common.modulecore_1.2.401.v201408132036.jar
 create mode 100644 eclipse-java-mars-R-win32-x86_64/eclipse/plugins/org.eclipse
.wst.common.project.facet.core_1.4.300.v201111030423.jar
 create mode 100644 eclipse-java-mars-R-win32-x86_64/eclipse/plugins/org.eclipse
.wst.common.snippets_1.2.200.v201208080420.jar
 create mode 100644 eclipse-java-mars-R-win32-x86_64/eclipse/plugins/org.eclipse
.wst.common.ui_1.1.500.v200911182011.jar
 create mode 100644 eclipse-java-mars-R-win32-x86_64/eclipse/plugins/org.eclipse
.wst.common.uriresolver_1.2.200.v201505132009.jar
 create mode 100644 eclipse-java-mars-R-win32-x86_64/eclipse/plugins/org.eclipse
.wst.dtd.core_1.1.700.v201211012112.jar
 create mode 100644 eclipse-java-mars-R-win32-x86_64/eclipse/plugins/org.eclipse
.wst.dtd.ui.infopop_1.0.400.v201309112106.jar
 create mode 100644 eclipse-java-mars-R-win32-x86_64/eclipse/plugins/org.eclipse
.wst.dtd.ui_1.0.801.v201308100602.jar
 create mode 100644 eclipse-java-mars-R-win32-x86_64/eclipse/plugins/org.eclipse
.wst.dtdeditor.doc.user_1.0.700.v201208081537.jar
 create mode 100644 eclipse-java-mars-R-win32-x86_64/eclipse/plugins/org.eclipse
.wst.internet.cache_1.0.700.v201211211430.jar
 create mode 100644 eclipse-java-mars-R-win32-x86_64/eclipse/plugins/org.eclipse
.wst.server.core_1.6.100.v201505132000.jar
 create mode 100644 eclipse-java-mars-R-win32-x86_64/eclipse/plugins/org.eclipse
.wst.sse.core_1.1.900.v201401092025.jar
 create mode 100644 eclipse-java-mars-R-win32-x86_64/eclipse/plugins/org.eclipse
.wst.sse.doc.user_1.1.100.v201208081537.jar
 create mode 100644 eclipse-java-mars-R-win32-x86_64/eclipse/plugins/org.eclipse
.wst.sse.ui.infopop_1.0.300.v201309112106.jar
 create mode 100644 eclipse-java-mars-R-win32-x86_64/eclipse/plugins/org.eclipse
.wst.sse.ui_1.3.400.v201505141512.jar
 create mode 100644 eclipse-java-mars-R-win32-x86_64/eclipse/plugins/org.eclipse
.wst.standard.schemas_1.0.700.v201304171715.jar
 create mode 100644 eclipse-java-mars-R-win32-x86_64/eclipse/plugins/org.eclipse
.wst.validation.infopop_1.0.300.v201309101952.jar
 create mode 100644 eclipse-java-mars-R-win32-x86_64/eclipse/plugins/org.eclipse
.wst.validation.ui_1.2.500.v201310231452.jar
 create mode 100644 eclipse-java-mars-R-win32-x86_64/eclipse/plugins/org.eclipse
.wst.validation_1.2.600.v201501211647.jar
 create mode 100644 eclipse-java-mars-R-win32-x86_64/eclipse/plugins/org.eclipse
.wst.xml.core_1.1.902.v201501211904.jar
 create mode 100644 eclipse-java-mars-R-win32-x86_64/eclipse/plugins/org.eclipse
.wst.xml.ui.infopop_1.0.400.v201309112106.jar
 create mode 100644 eclipse-java-mars-R-win32-x86_64/eclipse/plugins/org.eclipse
.wst.xml.ui_1.1.501.v201501212057.jar
 create mode 100644 eclipse-java-mars-R-win32-x86_64/eclipse/plugins/org.eclipse
.wst.xmleditor.doc.user_1.0.700.v201208081537.jar
 create mode 100644 eclipse-java-mars-R-win32-x86_64/eclipse/plugins/org.eclipse
.wst.xsd.core_1.1.900.v201401141857.jar
 create mode 100644 eclipse-java-mars-R-win32-x86_64/eclipse/plugins/org.eclipse
.wst.xsd.ui_1.2.500.v201208081537.jar
 create mode 100644 eclipse-java-mars-R-win32-x86_64/eclipse/plugins/org.eclipse
.wst.xsdeditor.doc.user_1.0.800.v201208081537.jar
 create mode 100644 eclipse-java-mars-R-win32-x86_64/eclipse/plugins/org.eclipse
.xsd.edit_2.8.0.v20150601-0402.jar
 create mode 100644 eclipse-java-mars-R-win32-x86_64/eclipse/plugins/org.eclipse
.xsd_2.11.0.v20150601-0402.jar
 create mode 100644 eclipse-java-mars-R-win32-x86_64/eclipse/plugins/org.hamcres
t.core_1.3.0.v201303031735.jar
 create mode 100644 eclipse-java-mars-R-win32-x86_64/eclipse/plugins/org.jsoup_1
.7.2.v201411291515.jar
 create mode 100644 eclipse-java-mars-R-win32-x86_64/eclipse/plugins/org.junit_4
.12.0.v201504281640/META-INF/ECLIPSE_.RSA
 create mode 100644 eclipse-java-mars-R-win32-x86_64/eclipse/plugins/org.junit_4
.12.0.v201504281640/META-INF/ECLIPSE_.SF
 create mode 100644 eclipse-java-mars-R-win32-x86_64/eclipse/plugins/org.junit_4
.12.0.v201504281640/META-INF/MANIFEST.MF
 create mode 100644 eclipse-java-mars-R-win32-x86_64/eclipse/plugins/org.junit_4
.12.0.v201504281640/META-INF/eclipse.inf
 create mode 100644 eclipse-java-mars-R-win32-x86_64/eclipse/plugins/org.junit_4
.12.0.v201504281640/about.html
 create mode 100644 eclipse-java-mars-R-win32-x86_64/eclipse/plugins/org.junit_4
.12.0.v201504281640/about_files/cpl-v10.html
 create mode 100644 eclipse-java-mars-R-win32-x86_64/eclipse/plugins/org.junit_4
.12.0.v201504281640/junit.jar
 create mode 100644 eclipse-java-mars-R-win32-x86_64/eclipse/plugins/org.junit_4
.12.0.v201504281640/plugin.properties
 create mode 100644 eclipse-java-mars-R-win32-x86_64/eclipse/plugins/org.sat4j.c
ore_2.3.5.v201308161310.jar
 create mode 100644 eclipse-java-mars-R-win32-x86_64/eclipse/plugins/org.sat4j.p
b_2.3.5.v201404071733.jar
 create mode 100644 eclipse-java-mars-R-win32-x86_64/eclipse/plugins/org.slf4j.a
pi_1.7.2.v20121108-1250.jar
 create mode 100644 eclipse-java-mars-R-win32-x86_64/eclipse/plugins/org.slf4j.i
mpl.log4j12_1.7.2.v20131105-2200.jar
 create mode 100644 eclipse-java-mars-R-win32-x86_64/eclipse/plugins/org.tukaani
.xz_1.3.0.v201308270617.jar
 create mode 100644 eclipse-java-mars-R-win32-x86_64/eclipse/plugins/org.w3c.css
.sac_1.3.1.v200903091627.jar
 create mode 100644 eclipse-java-mars-R-win32-x86_64/eclipse/plugins/org.w3c.dom
.events_3.0.0.draft20060413_v201105210656.jar
 create mode 100644 eclipse-java-mars-R-win32-x86_64/eclipse/plugins/org.w3c.dom
.smil_1.0.1.v200903091627.jar
 create mode 100644 eclipse-java-mars-R-win32-x86_64/eclipse/plugins/org.w3c.dom
.svg_1.1.0.v201011041433.jar
 create mode 100644 eclipse-java-mars-R-win32-x86_64/eclipse/readme/readme_eclip
se.html
 create mode 100644 eclipse-jee-mars-R-win32.zip
 create mode 100644 readme.md

C:\Users\KAyers\Desktop>git push
fatal: No configured push destination.
Either specify the URL from the command-line or configure a remote repository us
ing

    git remote add <name> <url>

and then push using the remote name

    git push <name>


C:\Users\KAyers\Desktop>git push readme.md
warning: push.default is unset; its implicit value has changed in
Git 2.0 from 'matching' to 'simple'. To squelch this message
and maintain the traditional behavior, use:

  git config --global push.default matching

To squelch this message and adopt the new behavior now, use:

  git config --global push.default simple

When push.default is set to 'matching', git will push local branches
to the remote branches that already exist with the same name.

Since Git 2.0, Git defaults to the more conservative 'simple'
behavior, which only pushes the current branch to the corresponding
remote branch that 'git pull' uses to update the current branch.

See 'git help config' and search for 'push.default' for further information.
(the 'simple' mode was introduced in Git 1.7.11. Use the similar mode
'current' instead of 'simple' if you sometimes use older versions of Git)

fatal: The current branch master has no upstream branch.
To push the current branch and set the remote as upstream, use

    git push --set-upstream readme.md master


C:\Users\KAyers\Desktop>git push --set-upstream readme.md master
fatal: Invalid gitfile format: readme.md
fatal: Could not read from remote repository.

Please make sure you have the correct access rights
and the repository exists.

C:\Users\KAyers\Desktop>git push --set-upstream readme.md master
```

## Summary
I tried to do the markdown assignment by creating a web page with my java project displayed.
