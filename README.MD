# AgentSlang Source code.
 * This files are part of AgentSlang Project (http://agent.roboslang.org/).

 * AgentSlang is free software: you can redistribute it and/or modify
 * it under the terms of the GNU Lesser General Public License as published by
 * the Free Software Foundation, version 3 of the License and CECILL-B.
 
 * This program is distributed in the hope that it will be useful,
 * but WITHOUT ANY WARRANTY; without even the implied warranty of
 * MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE. See the
 * GNU Lesser General Public License for more details.
 
 * You should have received a copy of the GNU Lesser General Public License
 * along with this program. If not, see <http://www.gnu.org/licenses/>.
 *
 * The CECILL-B license file should be a part of this project. If not,
 * it could be obtained at  <http://www.cecill.info/>.
 
 * The usage of this project makes mandatory the authors citation in
 * any scientific publication or technical reports. For websites or
 * research projects the AgentSlang website and logo needs to be linked
 * in a visible area. 
 


# Help
 * you can find Documents about Each component in Doucments Folder and index.html

# Installation
 * for running this component you need to install 
 * Java JDK 1.8 
 * Python 3
 
 
# Linux installation
	How to build “agentslang” on Ubuntu? 
	1.	apt-get update & apt-get upgrade

	2. Install JDK8 using the following command. 
	sudo apt-get install openjdk-8-jdk
	3. Install Git using the following command.
	sudo apt-get install git
	4. Install Gradle using the following command.
	sudo apt install gradle
	5. Create a folder in order to clone the agentslang source code and go to that folder.
	6. Clone agentslang sourcecode from INSA git using following command (enter your username and password when you asked for).
	git clone https://monprojet.insa-rouen.fr/git/nareca_final_version.git
	7. Go to the following folder inside cloned items.
	{Path}/nareca_final_version/Code/AgentSlang
	8. Give permission to run gradlew bash using the following command.
	chmod u+x gradlew
	9. Build it using the following command.
	./gradlew installDist 
	10. The output execuatble version will be in the following folder.
	{Path}/nareca_final_version/code/AgentSlang/AgentSlang/build/install/AgentSlang


 