"use client";

import React from 'react';

export default function DeliveryDashboard() {
  // --- Inline Styles Configuration ---
  const styles = {
    pageContainer: {
      display: 'flex',
      justifyContent: 'center',
      alignItems: 'center',
      minHeight: '100vh',
      backgroundColor: '#f4f4f5',
      fontFamily: '-apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, Helvetica, Arial, sans-serif',
      margin: 0,
      padding: 0,
    },
    mobileWrapper: {
      width: '100%',
      maxWidth: '500px',
      backgroundColor: '#ffffff',
      minHeight: '100vh', // Full height on mobile
      display: 'flex',
      flexDirection: 'column',
      alignItems: 'center',
      padding: '24px',
      boxSizing: 'border-box',
      boxShadow: '0 4px 20px rgba(0,0,0,0.1)',
    },
    header: {
      display: 'flex',
      flexDirection: 'column',
      alignItems: 'center',
      marginBottom: '30px',
      width: '100%',
    },
    logo: {
      width: '80px',
      height: 'auto',
      marginBottom: '12px',
    },
    title: {
      fontSize: '22px',
      fontWeight: '700',
      color: '#ff6600', // MishTee Orange
      margin: 0,
      textAlign: 'center',
    },
    statusContainer: {
      display: 'flex',
      alignItems: 'center',
      backgroundColor: '#e6fffa',
      padding: '8px 16px',
      borderRadius: '20px',
      marginBottom: '30px',
      border: '1px solid #b2f5ea',
    },
    statusDot: {
      width: '10px',
      height: '10px',
      backgroundColor: '#10b981', // Green
      borderRadius: '50%',
      marginRight: '8px',
      animation: 'pulse 2s infinite', // Uses the keyframes defined below
    },
    statusText: {
      color: '#065f46',
      fontSize: '14px',
      fontWeight: '600',
    },
    taskCard: {
      width: '100%',
      backgroundColor: '#fff',
      borderRadius: '16px',
      padding: '20px',
      boxShadow: '0 10px 15px -3px rgba(0, 0, 0, 0.1), 0 4px 6px -2px rgba(0, 0, 0, 0.05)',
      border: '1px solid #f0f0f0',
      marginBottom: '24px',
      boxSizing: 'border-box',
    },
    cardLabel: {
      fontSize: '12px',
      textTransform: 'uppercase',
      color: '#6b7280',
      letterSpacing: '0.05em',
      marginBottom: '8px',
      display: 'block',
    },
    customerName: {
      fontSize: '20px',
      fontWeight: '700',
      color: '#1f2937',
      marginBottom: '4px',
    },
    addressDetails: {
      fontSize: '14px',
      color: '#4b5563',
      lineHeight: '1.5',
    },
    actionButton: {
      width: '100%',
      padding: '16px',
      backgroundColor: '#ff6600', // MishTee Orange
      color: 'white',
      border: 'none',
      borderRadius: '12px',
      fontSize: '16px',
      fontWeight: '600',
      cursor: 'pointer',
      boxShadow: '0 4px 6px rgba(255, 102, 0, 0.3)',
      transition: 'transform 0.1s ease',
    },
  };

  return (
    <div style={styles.pageContainer}>
      {/* Injecting a style tag just for the keyframe animation 
        since inline styles cannot declare @keyframes.
      */}
      <style>{`
        @keyframes pulse {
          0% { box-shadow: 0 0 0 0 rgba(16, 185, 129, 0.7); transform: scale(1); }
          70% { box-shadow: 0 0 0 10px rgba(16, 185, 129, 0); transform: scale(1); }
          100% { box-shadow: 0 0 0 0 rgba(16, 185, 129, 0); transform: scale(1); }
        }
      `}</style>

      <div style={styles.mobileWrapper}>
        {/* Header Section */}
        <header style={styles.header}>
          <img 
            src="https://raw.githubusercontent.com/sudhir-voleti/mishtee-magic/main/mishTee_logo.png" 
            alt="mishTee Logo" 
            style={styles.logo}
          />
          <h1 style={styles.title}>mishTee Delivery Mitra</h1>
        </header>

        {/* Status Bar */}
        <div style={styles.statusContainer}>
          <div style={styles.statusDot}></div>
          <span style={styles.statusText}>Agent Online</span>
        </div>

        {/* Task Card */}
        <div style={styles.taskCard}>
          <span style={styles.cardLabel}>Current Task</span>
          <div style={styles.customerName}>Deliver to: Arjun Mehta</div>
          <div style={styles.addressDetails}>
            Flat 402, Green Valley Apts,<br/>
            Gachibowli, Hyderabad
          </div>
        </div>

        {/* Action Button */}
        <button 
          style={styles.actionButton}
          onMouseDown={(e) => e.currentTarget.style.transform = 'scale(0.98)'}
          onMouseUp={(e) => e.currentTarget.style.transform = 'scale(1)'}
        >
          Start Navigation
        </button>
      </div>
    </div>
  );
}
