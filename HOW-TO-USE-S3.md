# How to Use AWS S3

## Getting Started
You will need to create an account and then setup the necessary authentication to secure it. Since this maybe your first time using the services you will click on the square (or hamberger) to the top left to find the 
specific services that you are looking for or if you already know what you are attempting to use, enter it into the search bar. 

Remember that once you have accessed this service, it now shows up in the listed recently visited services. 

## What's Next....
Remember that this account is super secure and only you have the key to allow access. With that being said, here's how to setup the bucket (file folder/storage drive) for your project....

### The Steps:
- Click Create Bucket from the S3 page.
- Chose a unique name for your bucket from the setup screen. (This is also where you can set the necesssary access permissions as well. Not shown in the demo.)
- Click create bucket
- From the bucket page, click on the permissions tab, then click edit on the section labled Bucket Policy
- Once in the Bucket policy screen, to the right side, you should see generate policy, click that.
- On the Policy screen the steps...
- - Select the policy type which will be S3 (since that is the bucket type that we have setup)
  - If you would like anyone in the public to access the bucket, add a star * to the principle field.
  - The AWS services field auto populates to the S3 service. Now you have to select the action. In this case GetObject.
  - Click Generate Policy. Then copy the policy from the pop up screen.
  - Click edit in the section labled block policy and then paste the policy into the section followed by clicking save changes.
- These steps now allow you to be able to setup a bucket securely and access the public link

  ## The Link and ScreenShots
  [MyPicsDemo](https://mypicsdemo.s3.us-east-2.amazonaws.com/a%20representation%20of%20a%20time%20warp.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIA47GCAHX7SMLAWH2L%2F20241207%2Fus-east-2%2Fs3%2Faws4_request&X-Amz-Date=20241207T171349Z&X-Amz-Expires=300&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEJH%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLWVhc3QtMiJHMEUCIQCo5I3%2BAlFvpUcGHyOjEDr%2BGiqWYoHi5egv8JihNZMZAQIgHWrJcNb6t7vt9CX3MIRZnVP2PfbFPtdUhtJHvdQU6gAq6AIIShAAGgw4OTE2MTI1NzcyNzkiDOEAfsVPp%2Fc%2By5H%2F1yrFAmihKxCOo92MXPwWOziiyYCAqiEOX9%2FeJHW327mSrDVKfmvbh1%2BzDZ3f0xukiyhF7CFWc2M3QLdAXPKI0Mud1kxKbSfImNjJaOsgNal5HP1uszHESaV%2FuMENiNDxZemSeCx3fdKjz7SvwTyR%2Bqbum7MjlMvQSgEBPW%2FVXxcFI86Gg2%2FTzfTNP6vA3jmkg%2BR06l7keRx00i9GRnw6MH75GVrUUSkHbrV5YP%2BhR7V5%2BXaFXOotl3F3EKnJ4ebG0QiY2DmFFdZNggewVD2mwki%2BjNxG%2Bmy58YiBng8oEz3OXwteH51sJeHQNuNO69ljAPq7Dn%2B1OuF4fmllx8EdUreZyOq0RWvy%2FTqOBk%2FVQ1MoUwnlDgAJmEMCnMUSCd4BTlv4ATqjw3ikGrdeaQDS%2BnssBCIFbMSLPqwiFmnr%2BFGVEJB0J4Agb%2Fcwu8%2FRugY6swKZ7mpjBqrmVgIjEODth3CcRA7M%2Bbaz%2FdwYnPUgDhfxWdRm6TIHaJdfMaROYfeuqoJp2MOXxB%2F7EJox6CPpO7xgkGLjHQALnfx%2FZeUWjurVqAjob%2FcPlytw2ozYJymNRCEVKHZseUVsZNd4MtnyY4AL04gPc6uqIs6kq33A5w8ZUSwf3mMx7B5CqTC0x4cieLYQMUTPoSXc0GeG%2BrJ1hYeXPZqwQNVk9lVYlrRrjLFbWelzJzvT4BnL%2B5Q8oET95VZrOCDtguThRJe3x0v3PN%2BEwjU2V4x4%2BRDqaauCpdsS79v2D4p8SrdgvUh5U%2BrBWroMgFBSMAxw89I%2B13ZueV%2B%2FbjcYha5UhkAEBGub5fIN%2BxrRCqY%2FFEdCgC7brNdz6wSnZPCkvYQ83jji6cM3TYAs4%2BPf&X-Amz-Signature=45bb131b18ade412f3cab730e3ac05ae2a2cc22677b1ff4db2b6de047f329b0c&X-Amz-SignedHeaders=host&response-content-disposition=inline)
  [MyPicsDemo](https://mypicsdemo.s3.us-east-2.amazonaws.com/filmtriviagame.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIA47GCAHX7SMLAWH2L%2F20241207%2Fus-east-2%2Fs3%2Faws4_request&X-Amz-Date=20241207T171442Z&X-Amz-Expires=300&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEJH%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLWVhc3QtMiJHMEUCIQCo5I3%2BAlFvpUcGHyOjEDr%2BGiqWYoHi5egv8JihNZMZAQIgHWrJcNb6t7vt9CX3MIRZnVP2PfbFPtdUhtJHvdQU6gAq6AIIShAAGgw4OTE2MTI1NzcyNzkiDOEAfsVPp%2Fc%2By5H%2F1yrFAmihKxCOo92MXPwWOziiyYCAqiEOX9%2FeJHW327mSrDVKfmvbh1%2BzDZ3f0xukiyhF7CFWc2M3QLdAXPKI0Mud1kxKbSfImNjJaOsgNal5HP1uszHESaV%2FuMENiNDxZemSeCx3fdKjz7SvwTyR%2Bqbum7MjlMvQSgEBPW%2FVXxcFI86Gg2%2FTzfTNP6vA3jmkg%2BR06l7keRx00i9GRnw6MH75GVrUUSkHbrV5YP%2BhR7V5%2BXaFXOotl3F3EKnJ4ebG0QiY2DmFFdZNggewVD2mwki%2BjNxG%2Bmy58YiBng8oEz3OXwteH51sJeHQNuNO69ljAPq7Dn%2B1OuF4fmllx8EdUreZyOq0RWvy%2FTqOBk%2FVQ1MoUwnlDgAJmEMCnMUSCd4BTlv4ATqjw3ikGrdeaQDS%2BnssBCIFbMSLPqwiFmnr%2BFGVEJB0J4Agb%2Fcwu8%2FRugY6swKZ7mpjBqrmVgIjEODth3CcRA7M%2Bbaz%2FdwYnPUgDhfxWdRm6TIHaJdfMaROYfeuqoJp2MOXxB%2F7EJox6CPpO7xgkGLjHQALnfx%2FZeUWjurVqAjob%2FcPlytw2ozYJymNRCEVKHZseUVsZNd4MtnyY4AL04gPc6uqIs6kq33A5w8ZUSwf3mMx7B5CqTC0x4cieLYQMUTPoSXc0GeG%2BrJ1hYeXPZqwQNVk9lVYlrRrjLFbWelzJzvT4BnL%2B5Q8oET95VZrOCDtguThRJe3x0v3PN%2BEwjU2V4x4%2BRDqaauCpdsS79v2D4p8SrdgvUh5U%2BrBWroMgFBSMAxw89I%2B13ZueV%2B%2FbjcYha5UhkAEBGub5fIN%2BxrRCqY%2FFEdCgC7brNdz6wSnZPCkvYQ83jji6cM3TYAs4%2BPf&X-Amz-Signature=c37aad3cc3701ec6013630a5b09ddc0928510ec20df9a36031731d4e68d78eaa&X-Amz-SignedHeaders=host&response-content-disposition=inline)
  
![List](/Images/BUCKETLIST.png)
![Contents](/Images/BUCKETCONTENTS.png)
![BlockSettings](/Images/BLOCKPOLICYSETTING.png)
![GeneratePolicy](/Images/GENERATEPOLICY.png)
![ARN](/Images/ARN.png)
![BucketPolicy](/Images/BUCKETPOLICY.png)
![ARN](/Images/ARN.png)