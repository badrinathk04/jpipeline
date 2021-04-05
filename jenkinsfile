pipeline
{
	agent any
	stages
	{
		stage("build")
		{
			steps
			{
				sh '''
				#!/bin/bash
				
				git clone https://github.com/badrinathk04/c_project.git
				cd /home/ec2-user/.jenkins/c_project
				make '''
			}
		}
	}

}
