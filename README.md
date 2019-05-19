# usage  

let factory = CMSampleBuffer.Factory()  
let audioSampleBuffer = factory.createSampleBufferBy(pcm: pcm)  
let videoSampleBuffer = factory.createSampleBufferBy(mtlTexture: texture)  

